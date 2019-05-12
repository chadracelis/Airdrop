#Airdrop 

//////////DEPLOYING CONTRACTS/////////////////
1. Go to Remix - Solidity IDE and copy and paste both files

2. Under Airdrop Tokens file, deploy "Chad Coin" Contract

3. Under Airdrop Contract file, deploy 'Airdrop' Contract with arguments ~
   'Address of "Chad Coin" Contract
   'Address of deployer of "Chad Coin" Contract
   'Fixed amount of tokens to airdrop'
   
4. Access 'Chad Coin' Contract, go to 'approve' function and use arguments below and then click approve
   'Address of "Airdrop" Contract
   'Amount of tokens allowed to airdrop in total'
   
   
/////////INTERACTING WITH AIRDROP////////////////
1. Create or use an existing MyEtherWallet address
2. Go to 'Contracts' tab under MyEtherWallet and copy and paste address and ABI of 'Airdrop' Contract
3. Click access, select function 'drop' and finally generate transaction
