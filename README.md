# How to test

## Install our custom Metamask-Flask

- Download our custom Metamask-Flask extension which already includes the NuFi Cardano snap ([Chrome](https://github.com/nufi-official/metamask-snap-demo/releases/download/0.0.1/nufi-snap-demo-metamask-ext-build-chrome-0.0.1.zip)).
- Open Chrome.
- Open a new Chrome profile to not interfere with standard Metamask and other extensions.
- In Chrome native to `Settings` > `Extensions`.
  * Or go straight to `chrome://extensions`
- Activate "Developer mode".
- At the top, click `Load unpacked`.
- Choose your unzipped Chrome extension folder.
- Open the already installed Metamask-Flask extension and set up your account.

## Test using forked [adaplays](https://github.com/vacuumlabs/nufi-adaplays.xyz) testing dapp
- Navigate to [testing dapp](https://nufi-demo-snap-ef00b1df8cce.herokuapp.com/).
- Click `Connect` and then choose `Metamask (Flask)`.
- Confirm all snap installations.
- Confirm all permissions.
- Choose a password.
- Fund your wallet (we are using Cardano preprod network).
- Create a game according to the dapp.
- Sign transaction.
- Wait until the game move expires.
- Click on "Get your funds back".
- Sign transaction.

## Troubleshooting

If experiencing unexpected behavior, please try refreshing the page and repeat the process.
Always `Get your funds back` (see above) after making the move, as otherwise, the dapp may not
work correctly with other accounts.

In case of any issues please reach out to us at [TODO: email]

