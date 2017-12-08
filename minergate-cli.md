# Minergate-cli

There doesn't seem to be any documentation on the Minergate-CLI instance. If anyone knows more info message/comment

### Download and Install

* Debian & Ubuntu * 
``` sudo apt-get update && wget https://minergate.com/download/deb-cli -O minergate-cli.deb && sudo dpkg -i minergate-cli.deb ```

### Run the program

minergate-cli -user <YOUR@EMAIL> -{coin core}
``` minergate-cli -user YOUR@EMAIL -XMR 2 ```
If you dont put a core number, then it will use all cores


#### Coins
Apperently the CLI doesnt currently support all the coins the gui does? But I cant find any documentation on this so....


* Monero = `-XMR` 
* Fantom Coin = `-FCN` 
* Both Fantom and Monero = `-FCN+XMR` 
* 



