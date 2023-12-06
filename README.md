# NuFi Metamask snap Widget

We are looking for further funding for this project through [Catalyst grant](https://cardano.ideascale.com/c/idea/113367)

<img width="1512" alt="Screenshot 2023-12-06 at 10 46 56" src="https://github.com/nufi-official/metamask-snap-demo/assets/10008234/e0d8fec7-8b56-4024-b238-d14697d49686">
<img width="1511" alt="Screenshot 2023-12-06 at 10 46 33" src="https://github.com/nufi-official/metamask-snap-demo/assets/10008234/afa14b84-2aab-4234-ae3a-d13c4d75ddc7">


## How to test

### Install our custom Metamask-Flask

- Download our custom Metamask-Flask wallet extension which already includes the NuFi Cardano Snap (download it for Chrome [here](https://github.com/nufi-official/metamask-snap-demo/releases/download/0.0.1/nufi-snap-demo-metamask-ext-build-chrome-0.0.1.zip)). This download needs to be extracted (i.e. unzipped) before it can be installed.
- Open Chrome – Please try this prototype in a new Chrome profile (with no extensions) or at least disable all wallet extensions first.
- Open Extensions:
  * Click the Extensions icon, then click `Manage extensions`; or
  * Open the menu and click `Settings > Extensions`; or
  * Enter `chrome://extensions` in the address bar
- Activate "Developer mode" (top right).
- Click `Load unpacked` (top left) and choose the file you just downloaded and unzipped.
- Choose your unzipped Chrome extension folder.
- Once installed, open the Metamask-Flask extension and set up your account.

### Test using forked [adaplays](https://github.com/vacuumlabs/nufi-adaplays.xyz) testing dApp

#### Connect

- Navigate to the [testing dapp here](https://nufi-demo-snap-ef00b1df8cce.herokuapp.com/).
  * Note: this is just a testing dApp and is not part of our solution.
- Click `Connect` and then choose `Metamask (Flask)`.
- Confirm all Snap installations.
- In the popup that appears, confirm the connection.
- Finally, choose a game password (this is required by the dApp and is unrelated to our product).

#### Fund your wallet
- Fund your wallet by claiming test ADA from this [faucet](https://docs.cardano.org/cardano-testnet/tools/faucet/) (we are using Cardano Preprod, so be sure to select `Preprod Testnet`).
- You can find your wallet’s receiving address in the widget (click Receive).
  * You will have to refresh the dApp page and re-login (by clicking `Connect -> Metamask (Flask)` button) to re-load your balance.

#### Tasks
- Inspect the content of the NuFi floating wallet widget.
- Create a game by following the instructions on the dApp.
- The NuFi floating widget should show a `Sign transaction` prompt.
- Sign the transaction.
- Wait until the game move expires.
- Click on Get your funds back.
- The NuFi floating widget should show a `Sign transaction` prompt.
- Sign the transaction.

### Troubleshooting

If experiencing unexpected behavior, please try refreshing the page and repeat the process.
Always `Get your funds back` (see above) after making the move, as otherwise, the dapp may not
work correctly with other accounts.


