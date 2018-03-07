# cash

1. Introduction
2. Linux Installation
3. use

### Introduction:
cash is a library who convert a amount of currency in a other currency

### Linux Installation:

  install npm with
  ```sh
  $sudo apt-get install npm
  ```  
  install learnyounode with

  ```sh
  $sudo apt-get install learnyounode
  ```
  go in your folder "cash\" use the command
  ```sh
  $sudo npm install
  ```
  to install all the dependencies of the library cash

### Use:
  to have the usage and command,you can run :
  ```sh
  $node index.js
  ```
  to use the library you use the command
  ```sh
  $node index.js amount currencyComeFrom currencyToConvert currencyToConvert2 currencyToConvert3
  ```
  for exemple :
  convert 20 euro into 20 dollars ,20 pounds ,20 polish zloty
  ```sh
  $node index.js 20 eur usd gbp pln
  ```
you can just use :
```sh
$node index.js amount
```
and by default take the amount in usd and convert in eur,gbp and pln
