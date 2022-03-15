# Crypnance🪙
<p align="center"><img src="https://crypnance.net/assets/images/logo.png" height="300" /></p>
The project aims at building a cryptocurrency exchange platform where a user can connect its "MetaMask" wallet and can trade using eth. The project uses Solidity language and web3.js framework. This project therefore not only gets us to know about blockchain but also brings us closer to the world of cryptocurrency whose value is increasing day by day in the modern era.

## 📃Table Of Contents
* Introduction
  * About Project
  * Tech-Stack
  * File Structure
* Getting Started
* Glimpses
* Contributors


## 🙂Introduction

### 🤔About Project
The project aims at building a cryptocurrency exchange platform where a user can connect its "MetaMask" wallet and can trade using eth. The project uses Solidity language and web3.js framework. This project therefore not only gets us to know about blockchain but also brings us closer to the world of cryptocurrency whose value is increasing day by day in the modern era.Through HTML,CSS,JavaScript,React and Bootstrap,the Blockchain is deployed on a website. The website is on a local-host. This project enhances the knowledge of blockchain technology which has a very high potential in future.

### ⚙️Tech-Stack
<p align="center">
<a href="https://code.visualstudio.com/" title="VS Code"><img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" alt="VS Code" height="31" width="31" style="vertical-align:top; margin:4px"></a>
<a href="https://www.blockchain.com/" title="Blockchain"><img src="https://user-images.githubusercontent.com/84843295/146194516-a5a1dea3-b779-4a3f-8672-a02ead2267c6.png" alt="Block-Chain" width="31px" height="31px"></a>
<a href="https://web3js.readthedocs.io/en/v1.7.1/" title="Web3.js"><img src="https://repository-images.githubusercontent.com/24655114/c71c5800-6a8c-11e9-9117-8ec357c9f69e" alt="Web3.js" width="31px" height="31px"/></a>
<a href="https://www.w3.org/TR/html5/" title="HTML5"><img src="https://github.com/get-icon/geticon/raw/master/icons/html-5.svg" alt="HTML5" width="31px" height="31px"></a>
<a href="https://www.w3.org/TR/CSS/" title="CSS3"><img src="https://github.com/get-icon/geticon/raw/master/icons/css-3.svg" alt="CSS3" width="31px" height="31px"></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" title="JavaScript"><img src="https://github.com/get-icon/geticon/raw/master/icons/javascript.svg" alt="JavaScript" width="31px" height="31px"></a>
<a href="https://reactjs.org/" title="React"><img src="https://github.com/get-icon/geticon/raw/master/icons/react.svg" alt="React" width="31px" height="31px"></a>
<a href="https://getbootstrap.com/" title="Bootstrap"><img src="https://github.com/get-icon/geticon/blob/master/icons/bootstrap.svg" alt="Bootstrap" width="31px" height="31px"></a>
</p>

### 📁File Structure
```
Crypnance                      
├─ migrations                  
│  ├─ 1_initial_migration.js   
│  └─ 2_deploy_contracts.js    
├─ public                      
│  ├─ favicon.ico              
│  ├─ index.html               
│  └─ manifest.json            
├─ scripts                     
│  └─ seed-exchange.js         
├─ src                         
│  ├─ abis                     
│  │  ├─ Exchange.json         
│  │  ├─ Migrations.json       
│  │  ├─ SafeMath.json         
│  │  └─ Token.json            
│  ├─ components               
│  │  ├─ App.css               
│  │  ├─ App.js                
│  │  ├─ Balance.js            
│  │  ├─ Content.js            
│  │  ├─ MyTransactions.js     
│  │  ├─ Navbar.js             
│  │  ├─ NewOrder.js           
│  │  ├─ OrderBook.js          
│  │  ├─ PriceChart.config.js  
│  │  ├─ PriceChart.js         
│  │  ├─ Spinner.js            
│  │  └─ Trades.js             
│  ├─ contracts                
│  │  ├─ Exchange.sol          
│  │  ├─ Migrations.sol        
│  │  └─ Token.sol             
│  ├─ flats                    
│  │  ├─ Exchange_flat.sol     
│  │  └─ Token_flat.sol        
│  ├─ store                    
│  │  ├─ actions.js            
│  │  ├─ configureStore.js     
│  │  ├─ interactions.js       
│  │  ├─ reducers.js           
│  │  └─ selectors.js          
│  ├─ helpers.js               
│  ├─ index.js                 
│  └─ serviceWorker.js         
├─ test                        
│  ├─ Exchange.test.js         
│  ├─ helpers.js               
│  └─ Token.test.js            
├─ flatten.sh                  
├─ package-lock.json           
├─ package.json                
├─ README.md                   
└─ truffle-config.js           

 ```
 
## 💻Project Setup
In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

Note: this is a one-way operation. Once you `eject`, you can’t go back!

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

##  ⚒️Getting Started

Assuming you have git, follow the following process
1. Clone the Git Repo:
   ```
   $ git clone https://github.com/psankhe28/Crypnance.git
   ```
2. Go into the Repo directory
   ```
   $ cd ../Crypnance
   ```
   
3. Run `npm run start` command in terminal
   ```
   $ npm run start
   ```
4. Connect your `metamask` account.
5. Now you can see the transactions done by that particular wallet.

## 📷Glimpses
![image](https://lh3.googleusercontent.com/xshv1fC-bRpm6gX1t_DrVfY-swqldgi8n2rktDPvSpiuYJbf_jL4o0yUYmlOO8Nx-XNmye2N1uKFxh4UBicU1Ln63j-vQulkXwo0Kh2hgyyN4ZPsYzbf_GajEo-Py8gczregbr-7Ig=w2400)


## 👨‍💻Contributors
* [Pratiksha Sankhe](https://github.com/psankhe28)
* [Apurv Sonawane](https://github.com/Apurv428)

## 🔧 Project Diagram
![Project workflow](https://i.gyazo.com/7328e5390fa92f147077ff5c963abf1b.png)
