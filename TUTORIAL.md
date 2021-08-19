# AVAX ERC20 Tutorial
> A simple tutorial to make an ERC20 token on the AVAX network
### Pre-reqs:
 - MetaMask Extension (https://metamask.io) connected to the Avalanche network. (instructions here https://pangolin.exchange/tutorials/getting-started)
 - A bit of AVAX in your wallet for gas.
 - Access to https://remix.ethereum.org/
Got all that? OK, let's go!

### Step 1: Code </>
1) Open /contract20.sol
2) Copy the WHOLE file's content.
3) Open https://remix.ethereum.org/
4) Make a new file in Remix called `Token.sol`.
5) Paste the code in the file.
6) Search for `contract Consts {`.
7) That defines the parameters for your token, and is pretty easy to understand, but I'll explain.
7.1) `uint public constant TOKEN_DECIMALS = 18;` Is the token's decimals
7.2) `uint8 public constant TOKEN_DECIMALS_UINT8 = 18;` Is the token's decimals in uint8 form
7.3) `uint public constant TOKEN_DECIMAL_MULTIPLIER = 10 ** TOKEN_DECIMALS;` Is the decimals multiplier
7.4) `string public constant TOKEN_NAME = "YourToken";` <-- This is important, it's your token's name.
7.5) `string public constant TOKEN_SYMBOL = "YOUR";` <-- Also important, your token's symbol. Normally 2-5 alphanumberical characters. 
7.6) `bool public constant PAUSED = false;` Is your token paused?
7.7) `address public constant TARGET_USER = 0x3e522051A9B1958Aa1e828AC24Afba4a551DF37d;` <-- IMPORTANT, your address. If you don't change that you're basically saying that the initial supply is mine :)
7.8) `bool public constant CONTINUE_MINTING = true;` Allow minting?
8) OK, customisation done.
9) Click the solidity icon (second down from the top left)
10) Select solidity 0.4.24 from the drop-down.
11) Click 'Compile Token.sol'
12) Now, select the tab underneath the Solidity icon
13) You should see a dropdown with JavaScript VM (London) as the default.
14) Change that to Injected Web3 and allow metamask to connect.
15) Select 'MainToken (Token.sol)' from the list below 'CONTRACT' (should be 'BasicToken (Token.sol)' by default).
16) Then, click the 'Deploy' button and approve the transaction.
17) Done!
### Step 2: What now? 
Your ERC20 token is on the Avalanche network!
You can choose to mint new tokens, burn some of the supply, etc.
You can grow your project, and build a network.
You can build a website or more!
You can build a payment system!
Build the future!
### Donate?
I'm entering the dev contest here: https://medium.com/avalancheavax/avalanche-launches-developer-tutorial-contest-with-50k-in-prizes-7d8b4422399f, but feel free to donate directly here! `0x3e522051A9B1958Aa1e828AC24Afba4a551DF37d`
## Bye! 💻
