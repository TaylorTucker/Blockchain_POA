# Proof of Authority Development Chain


![blockchain](https://www.paymentsjournal.com/wp-content/uploads/2020/03/1027-scaled.jpg)


## Instrucions to start the network.


1. Use geth to initialize node1 & node2 and connect to "tucker" network
  
  For Node 1 
         ./geth init tucker.json --datadir node1
  ----
  For Node 2
         ./geth init tucker.json --datadir node1
         
2. Launch nodes into mining mode. Use "dog" as the password for each node.

 For Node 1 
        ./geth --datadir node1 --unlock "0x93b3Ec56A63BcA620e488F70b9dC1542764aDe19" --mine --rpc --allow-insecure-unlock
 ---
 For Node 2
        ./geth --datadir node2 --unlock "0x952E5A1fA4d7E0c7E2283E121772585677576448" --mine --port 30304 --bootnodes "enode://8c523eb5346bdeeb014a48f3361275ebe7a1676d3e3ab9cbc94c6b2c8b6abd7d955d186384123fe470f9773ff88f00bffd5be944325c8368a497b10390fba9a5@127.0.0.1:30303" --ipcdisable --allow-insecure-unlock




