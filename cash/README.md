# cash

First clone your repository project `https://github.com/Linaerith/3-musketeers`

```sh
❯ cd /path/to/workspace
❯ git clone git@github.com:YOUR_USERNAME/3-musketeers.git
```

Then, run these following command lines to install the cash project.

```sh
❯ cd /path/to/workspace/3-musketeers/cash
❯ npm i
```

The conversion by default is 1 USD (Dollar US) to EUR (Euro), GBP (British Pound Sterling) and JPY (Japanese Yen).
Run this one to do it.
```sh
❯ node bin/index.js
```

In order to convert any currency to other currencies, run this line. You can have more than one currency in the "to" argument.
```sh
❯ node bin/index.js <amount> <from> <to>
```
For instance, if you want to convert 10 US Dollars to Euro and Polish Zloty, here is what you have to run: 
```sh
❯ node bin/index.js 10 usd eur pln
```


Complete the cash/README.md file with a complete description of installation, usage... of the library
add JSDOC function block for the file cash/bin/cash.js
