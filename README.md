# NuFi Metamask snap Widget

We are looking for further funding for this project through [Catalyst grant](https://cardano.ideascale.com/c/idea/113367)

<img width="1512" alt="Screenshot 2023-12-06 at 10 46 56" src="https://github.com/nufi-official/metamask-snap-demo/assets/10008234/e0d8fec7-8b56-4024-b238-d14697d49686">
<img width="1511" alt="Screenshot 2023-12-06 at 10 46 33" src="https://github.com/nufi-official/metamask-snap-demo/assets/10008234/afa14b84-2aab-4234-ae3a-d13c4d75ddc7">


## How to test

### Install our custom Metamask-Flask

- Download our custom Metamask-Flask extension which already includes the NuFi Cardano snap ([Chrome](https://github.com/nufi-official/metamask-snap-demo/releases/download/0.0.1/nufi-snap-demo-metamask-ext-build-chrome-0.0.1.zip)).
- Open Chrome.
- Please try this prototype in a new Chrome profile or at least disable all wallet extensions in your Chrome.
- In Chrome native to `Settings` > `Extensions`.
  * Or go straight to `chrome://extensions`
- Activate "Developer mode".
- At the top, click `Load unpacked`.
- Choose your unzipped Chrome extension folder.
- Open the already installed Metamask-Flask extension and set up your account.

### Test using forked [adaplays](https://github.com/vacuumlabs/nufi-adaplays.xyz) testing dapp
- Navigate to [testing dapp](https://nufi-demo-snap-ef00b1df8cce.herokuapp.com/).
  * Note that this is just a testing dapp and is not part of the proposal itself.
- Click `Connect` and then choose `Metamask (Flask)`.
- Confirm all snap installations.
- In the popup that appears confirm connection.
- Choose a password (dapp specific, unrelated to our product).
- Fund your wallet via [faucet](https://docs.cardano.org/cardano-testnet/tools/faucet/) (we are using Cardano preprod network).
  * You will have to refresh the dapp page and re-login with `Connect -> Metamask (Flask)` button to reload your balance.
- Inspect the content of the NuFi floating widget.
- Create a game according to the dapp.
- The NuFi floating widget should show a sign transaction prompt.
- Sign transaction.
- Wait until the game move expires.
- Click on `Get your funds back`.
- The NuFi floating widget should show a sign transaction prompt.
- Sign transaction.

### Troubleshooting

If experiencing unexpected behavior, please try refreshing the page and repeat the process.
Always `Get your funds back` (see above) after making the move, as otherwise, the dapp may not
work correctly with other accounts.


