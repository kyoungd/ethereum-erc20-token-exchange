
testrpc -m "endorse change laundry novel emotion style fragile bunker party unhappy surface cushion"


Available Accounts
==================
(0) 0xbc3e536d9dae4c2f933421e54af421b6de53283d
(1) 0x9515da820ba59a8790b81486cf3ea9d1d49ef409
(2) 0x1f8deb8a9bebe9598e7780a43e7a25ba3718b1b5
(3) 0x83af643fcadecd88c842df18a8b1942703ee8354
(4) 0xff401c2c2f6ac781077d1ccb00bd2329729576f7
(5) 0xb9e6148d2bb992d6124ab8dcf23ce4353ada1817
(6) 0x4b0aae878f6845bca23ffefb504d714df0c75979
(7) 0x0dc63d29fd23492e32d31fcad5a907a950de8195
(8) 0x038ae095cc2fb9d1d4eab245845afc90875ce268
(9) 0xcb664f199bd0e3088699e88bbfa32566e61b7881

Private Keys
==================
(0) 23960f2896e119e0b4f991ca4de452137893e6ba963ae3735b2f3c2176a6c0b2
(1) c97e8073d147a015c0c4fbe8d773f994292ba20e2e06a175610b3466fe3fe49b
(2) 9839f497197edd4209b142b52850f06768b782114b89ae706acc56b9791f3b9a
(3) 8dae1975b520f823039f808e09dac03e9ecb8f834ee1a2fa4708d0ac49eb166b
(4) 75245e41c6e0d6fe96a62bb098079e1672a375adda5f8ba8fbdbae7d70741df2
(5) cfb26af298366136b0f9f1a7ee210ea867d4dfc18389d920565cfefba2cbbf76
(6) 0c970734637b10a6a6071d976c8baedb1bc112593ba43b7b8c4b2884b512f5c1
(7) 29c362ebda35cd39ad767d9b848c466b5d6677ba0d055b345733b2c143b1a902
(8) c23c34861456d6ce7c560eeadb0bbb027aec342fb97b61d1e0210a76fcc5556f
(9) 6269b5798e3acf004a4ff8238f7d06d9e26139de8b7a68890efd8b3370bd0801


Install geth
Install ethereum wallet

Open commmand window 1

copy genesis.json file to the following directory.
cd \users\kyoun\Desktop\CryptoCurrency\ethereum2
mkdir chaindata
geth --datadir=./chaindata init genesis.json
geth --datadir=./chandata

Open a command window 2

geth attach

Open the Ethereum Wallet
Click on the "Add Account".
Enter password and confirmation password.

Go back to command window 2 again.

miner.setEtherbase(eth.accounts[0])
miner.start()
-- ether is generated.
miner.stop()

download geth fast, but only for the first time.
geth --fast --cache=1024

PYTHON
C++

SSL
https://slproweb.com/products/Win32OpenSSL.html

GitBash
https://git-scm.com/downloads

NodeJS
https://nodejs.org/en/download/

geth --datadir=./chaindata/ --rpc  --rpccorsdomain "*"
geth --datadir=./chaindata/ --rpc --rpccorsdomain "*" --rpcapi=db,eth,web3,personal
geth --datadir=./chaindata/ --rpc --rpccorsdomain "*" --rpcapi=db,eth,web3,personal

geth --rpc --rpcport 8545 --rpcaddr 127.0.0.1 --rpccorsdomain "*" --rpcapi=db,eth,net,web3,personal

https://github.com/tomw1808/truffle_eth_class1
testrpc


ADD BOOTSTRAP TO TRUFFLE PACKAGE

webpack.config.js

module: {
    rules: [
      {yahoo
       test: /\.css$/,
       use: [ 'style-loader', 'css-loader' ]
     },
     { test: /\.scss$/, use: ['style-loader', 'css-loader', 'postcss-loader', 'sass-loader'] },
     {
       test: /\.woff2?(\?v=[0-9]\.[0-9]\.[0-9])?$/,
       use: 'url-loader?limit=10000'
     },
     {
       test: /\.(ttf|eot|svg)(\?[\s\S]+)?$/,
       use: 'file-loader'
     }
    ],
    loaders: [
      { test: /\.json$/, use: 'json-loader' },
      {
        test: /\.js$/,
        exclude: /(node_modules|bower_components)/,
        loader: 'babel-loader',
        query: {
          presets: ['es2015'],
          plugins: ['transform-runtime']
        }
      }
    ]
  }

 npm install --save bootstrap
 npm install --save-dev postcss-loader
 npm install --save-dev sass-loader
 npm install --save-dev url-loader
 npm install --save-dev file-loader
 npm install --save-dev node-sass


 npm install --save truffle-contract

 npm run dev  // react app

mkdir testdir
geth --datadir=./testdir --rinkeby --rpc --rpccorsdomain "*" --rpcapi=db,eth,net,web3,personal

"*"
geth attach
> eth.syncing

all accounts are saved in the chaindata/keystore.  Copy that to the new ./testdir/keystore

sign into your github and open another tab.  go to this site.
https://gist.github.com/
http://rinkeby.etherscan.io

truffle migrate --network rinkeby
