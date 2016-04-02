# Create an Ethereum Multisignature Wallet (OSX)

## Requirements

1. Ethereum-Wallet installed
2. 2 Accounts on the test network (Morden)
3. At least 1 Ether in each account

## Create the Multisignature Wallet

1. Open the Ethereum-Wallet and connect to Testnet
2. Copy the both account's address and paste them somewhere for later.
3. On the 'WALLETS' tab, scroll down to the 'Wallet Contracts' section and press the 'ADD WALLET CONTRACT' button

![Wallets tab](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/create/3a.png)
![Add Wallet Contract](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/create/3b.png)

4. Name the multisignature wallet

![Name it](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/create/4.png)

5. Select the first owner (an account)
6. Select 'MULTISIGNATURE WALLET CONTRACT'
7. Change the number of owners to 2
8. Change the amount of Ether an owner can send per day to 1 Ether
9. Add the address of the second owner
10. Press 'CREATE'

![Create Wallet](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/create/10.png)

11. Enter your password and press 'SEND TRANSACTION"

![Enter Password](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/create/11.png)
 
12. Keep a copy of the address they show you safe... it could take awhile to create the wallet

![Wallet Create](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/create/12.png)

## How to Backup your Accounts and Wallets

1. Create a folder called 'backups'
2. Go to 'Accounts' in the top menu, then 'Backup', then press 'Accounts'
 
![Accounts tab](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/backup/2.png)

3. That's the keystore for the main network. Back that up after this guide.
4. Navigate to the 'testnet' folder in the same directory

![Backup Directories](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459558272/guide/backup/4.png)

5. Backup the 'keystore' folder in 'backups/testnet'
6. Go to 'Accounts' in the top menu, then 'Backup', then press 'Application Data'
 
![Accounts tab](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/backup/6.png)

7. Backup the 'Mist' folder (somewhere in here are your wallets) in 'backups'.
8. Keep the 'backups' folder safe. You can't regenerate this. Don't mess up.

## How to import your Wallets

**I'm about to tell you to delete your wallets, and all the tokens and contracts you're watching. You need to backup all those addresses, json interfaces and data!!!**

1. Go to 'Accounts' in the top menu, then 'Backup', then press 'Application Data'
2. Delete the entire 'Mist' folder
3. Relaunch the 'Ethereum-Wallet', there should be no wallets there
 
![No Wallet](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/import/3.png)

4. On the 'WALLETS' tab, scroll down to the 'Wallet Contracts' section and press the 'ADD WALLET CONTRACT' button
5. Name the wallet
6. Select 'IMPORT WALLET'
7. Enter the wallet's address
8. There should be green writing saying that your account is an owner of the wallet.
9. Press 'CREATE'

![Import it!](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/import/9.png)
![Done](http://res.cloudinary.com/dqza9dw1h/image/upload/c_scale,w_800/v1459557802/guide/import/10.png)

My wallet address for donations and <3s: 0x1A416af553Faca53b4be48DCFB6E749C9737455D