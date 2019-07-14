:one: Navigate to Settings > Options > Wallets > Check 'Enable Masternodes Tab'

:two: Navigate to tools > debug log > Enter getaccount address mn1 > Then enter masternode genkey

:three: Send 2000 BTOK to address generated from getaccount address mn1 

:four: Navigate back to debug console > Enter 'masternode outputs'

:five: On VPS  download script 
 paste > https://github.com/PaulBPortfolio/BeetokMNScript/releases/download/v0.0.1/mn-install.sh

:six: Open masternode.config file enter **mn1 (Your VPS IP):1112 (Masternode Genkey) and Masternode outputs string save & close the file - restart wallet

:seven: On the masternode tab click the masternode and then click start alias. On the VPS enter startmasternode local false
