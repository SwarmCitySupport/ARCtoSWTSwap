# How do I exchange ARC for SWT?
<p dir="ltr"><span style="font-size: large;">See the <a href="https://github.com/swarmcity/sc-token/blob/master/token-exchange-miniwhitepaper.md#options-for-exchanging-my-tokens">Swarm CIty Github</a> for additional details about the token conversion process, or to find instructions on manual conversion.</span></p>
<p dir="ltr"><span style="font-size: large;"><strong>IMPORTANT NOTE</strong>: D<span>o not send tokens directly to the new token address using any wallet software ( MyCrypto / MyEtherWallet / Mist / MetaMask / etc. ) they will not be converted to SWT tokens this way, and will be lost if you do so.</span></span></p>
<p dir="ltr"><span><span style="font-size: large;">To initiate the ARC to SWT conversion process, you will start the by going to the Swarm City Terminal.</span></span></p>
<ul>
<li><span style="font-size: large;"><span id="docs-internal-guid-4d47cc0a-f6ab-4d13-8d5b-fc4b9901a289"><span>Visit </span><span><a href="https://swarm.city">https://swarm.city</a>&nbsp;and create a bookmark on your homepage</span></span></span></li>
<li><span style="font-size: large;"><span id="docs-internal-guid-4d47cc0a-f6ab-4d13-8d5b-fc4b9901a289"><span>Select "enter here"</span></span></span></li>
<li><span style="font-size: large;">Be sure to select "Create new user" although you already have an ARC wallet. All users must first create a new profile in the Swarm City Terminal</span></li>
<li><span style="font-size: large;">Click on "Yes, convert my tokens"</span></li>
</ul>
<p><span style="font-size: large;">Now you can either use your ARC 'json-file' backup or private key</span></p>
<ul>
<li><span style="font-size: large;">Choose "as a json-file"</span></li>
<li><span style="font-size: large;">Select the json-file associated with your wallet</span></li>
<li><span style="font-size: large;">Verify your password</span></li>
<li><span style="font-size: large;">UNLOCKING WALLET</span></li>
</ul>
<p><span style="font-size: large;">or</span></p>
<p><span style="font-size: large;">Load the wallet storing the ARC tokens you want to convert. All ARC tokens in this wallet will be automatically converted into SWT upon entry to the Terminal after selecting 'Enter here' and succesfully decrypting your wallet.</span></p>
<ul>
<li><span style="font-size: large;">Choose "I have ARC tokens on an external wallet" to use your private key</span></li>
<li><span style="font-size: large;">You will need to create a new password and confirm it</span></li>
<li><span style="font-size: large;">UNLOCKING WALLET</span></li>
</ul>
<p><span style="font-size: large;">NOTE: *Users can not specify partial conversion amounts, so be sure to remove any ARC that you do not wish to convert prior to initiating the conversion process. Use Etherscan.io at&nbsp;<a href="https://etherscan.io/">https://etherscan.io/</a> to check your wallet address balances.</span></p>
<p><span style="font-size: large;">ARC tokens will be AUTOMATICALLY detected and converted to SWT as long as your wallet also holds enough ETH to cover the transaction gas fees.</span></p>
<p><span style="font-size: large;">The ARC to SWT conversion process also requires a small amount of ether to cover the Ethereum blockchain transaction gas fees. This amount varies and is determined by the miners processing the block. Check&nbsp;MyEtherWallet at&nbsp;<a href="https://myetherwallet.github.io/knowledge-base/gas/what-is-gas-ethereum.html">https://mycrypto.github.io/knowledge-base/gas/what-is-gas-ethereum.html</a>&nbsp;for the current transaction gas fee amount.</span></p>
<p><span style="font-size: large;">If your wallet address doesn't hold enough ETH to cover the transaction fees associated with any/all transactions occuring on the Ethereum blockchain, then you will receive an error message, and the transaction will ultimately fail after attempting the conversion process. No worries, if the transaction fails your ARC balance is not affected.&nbsp;</span></p>
<p><span style="font-size: large;">To complete the transaction, send a small amount of ETH, approximately <code>20 GWEI</code><span>&nbsp;=&nbsp;</span><code>0.00042 ETH </code></span><span style="font-size: large;">to your ARC wallet public address. </span></p>
<p><span style="font-size: large;">The 3 step conversion process takes a few minutes to complete.</span></p>
<ul>
<li><span style="font-size: large;">First, the contract checks the wallet's ether balance. If the amount is sufficient, you will notice a "green checkmark"&nbsp;</span></li>
<li><span style="font-size: large;">Next, allowance is given to the new SWTConverter contract to receive the full balance of ARC tokens. This function moves the ARC tokens to the burn address. New SWT is minted, at a 1:1, rate on the same address that initially stored the ARC tokens. This may take a few minutes. You will again notice a "green checkmark"</span></li>
<li><span style="font-size: large;">Lastly, your balance is updated. The wallet now holds your freshly minted SWT!! You will notice a third "green checkmark" and receive "Congratulations". You can now view your SWT and ether balance, send SWT, and transact on the Swarm City Boardwalk.</span></li>
</ul>

# WHat happens to ARC tokens that are converted to SWT?
<p><span style="font-size: large;"><span>The ARC tokens will be destroyed immediately by being sent to the burn address,&nbsp;<span id="docs-internal-guid-35aa2414-f719-b6d7-eaa4-f1571a96911d"><span><a href="https://etherscan.io/token/0xAc709FcB44a43c35F0DA4e3163b117A17F3770f5?a=0x0000000000000000000000000000000000000000">https://etherscan.io/token/0xAc709FcB44a43c35F0DA4e3163b117A17F3770f5?a=0x0000000000000000000000000000000000000000</a>.</span></span></span></span></p>
<p><span style="font-size: large;">ARC tokens sent to this address are forever "locked" once they reach this burn address.&nbsp;<a href="https://en.bitcoin.it/wiki/Proof_of_burn">Burning</a>&nbsp;is a method of effectively destroying coins such that they can never be spent again. Coins can be burnt&nbsp;by sending them to an address, which are guaranteed to have no known or discoverable private key.</span></p>

# Why is there an ARC to SWT conversion?
<p><span style="font-size: large;">For the benefit of this project it was necessary to <a href="https://press.swarm.city/forking-a-brand-cde5de87d46a">fork the brand</a> from Arcade City to Swarm City. Therefore, use of the ARC token within the Swarm City DApp was no longer an acceptable option.</span></p>
<p><span style="font-size: large;">So, we integrated an exchange process into our DApp, indefinitely giving all ARC token holders the option to exchange ARC for SWT that can be used in the Swarm City ecosystem.&nbsp;&nbsp;</span></p>

# When can I exchange ARC for SWT?
<p><span style="font-size: large;"><span>You can start the exchange anytime, select "enter here" at&nbsp;</span><a class="postlink" href="https://legacy.swarm.city/">Swarm City</a>.</span></p>
<p><span style="font-size: large;">Exchange rate 1:1</span></p>
<p><span style="font-size: large;">This conversion process will always be available at <a href="https://swarm.city/">https://legacy.swarm.city</a>.&nbsp;</span></p>
<p><span style="font-size: large;">There is NO TIME LIMIT</span></p>

# What is the ARC to SWT conversion rate?
<p><span style="font-size: large;">The exchange rate is 1:1</span></p>
<p><span style="font-size: large;">Users will get 1 SWT in exchange for 1 ARC token.</span></p>
<p><span style="font-size: large;">This conversion rate is permanent.</span></p>
<p>&nbsp;</p>
<p><span style="font-size: large;">To initiate the ARC to SWT conversion, visit the Swarm City Terminal at <a href="https://swarm.city">https://legacy.swarm.city</a></span></p>
<p><span style="font-size: large;">Load the wallet storing the ARC tokens you want to convert. All ARC tokens in this wallet will be automatically converted into SWT upon entry to the Terminal after selecting Enter here and succesfully decrypting your wallet.</span></p>
<p><span style="font-size: large;">NOTE: *Users can not specify partial conversion amounts, so be sure to remove any ARC that you do not wish to convert prior to initiating the conversion process.</span></p>
<p><span style="font-size: large;">The ARC to SWT conversion process also requires a small amount of ether to cover the Ethereum blockchain transaction gas fees. This amount varies and is determined by the miners processing the block. Check <a href="https://mycrypto.github.io/knowledge-base/gas/what-is-gas-ethereum.html">M</a><a href="https://mycrypto.github.io/knowledge-base/gas/what-is-gas-ethereum.html">yCrypto</a> for the current gas fee amount.</span></p>
<p>&nbsp;</p>

# Is there a time limit for exchanging ARC to SWT?
<p><span style="font-size: large;"><span>There is no time limit on performing the conversion. This functionality will be permanently available in our contract.</span></span></p>

# Can I convert ARC without using the Swarm City Terminal?
<p><span style="font-size: large;"><span>Yes, the easiest way to convert ARC to SWT is to use the automatic conversion tool in the Swarm CIty Terminal, but technically savvy users can also perform the exchange manually. </span></span></p>
<p><span style="font-size: large;"><span>Find instructions&nbsp;</span><a class="postlink" href="https://github.com/swarmcity/sc-token/blob/master/token-exchange-miniwhitepaper.md#options-for-exchanging-my-tokens">here</a>.</span></p>

# I don't want to hodl SWT anymore, can I get an eth refund?
<p><span style="font-size: large;"><span>We will not refund ETH, but you can trade ARC tokens on one of the decentralized exchanges, like Etherdelta.&nbsp;</span></span></p>
<p><span style="font-size: medium;">ARC tokens are not listed on any major exchanges and are a bit harder to trade/sell. If you can not find someone who wants to trade for ARC tokens, you can convert your ARC to SWT and then sell/trade the SWT.</span></p>

# Can I send ARC from MyCrypto wallet directly to the SWT token contract?
<p><span style="font-size: large;">No, to exchange from ARC to SWT you will either need to use the automatic conversion tool or use the instructions provided <a href="https://github.com/swarmcity/sc-token/blob/master/token-exchange-miniwhitepaper.md#2-perform-the-token-exchange-yourself-advanced">here</a> to complete the conversion process manually.</span></p>
<p><span style="font-size: large;">Tokens sent directly to the Swarm City token contract will NOT be converted, and can not be recovered.</span></p>
<p><span style="font-size: large;">DO NOT SEND ANY TOKENS DIRECTLY TO THE SWARM CITY TOKEN CONTRACT.</span></p>
<p><span style="font-size: large;">ARC token burn address:&nbsp;<a href="https://etherscan.io/token/0xAc709FcB44a43c35F0DA4e3163b117A17F3770f5?a=0x0000000000000000000000000000000000000000">https://etherscan.io/token/0xAc709FcB44a43c35F0DA4e3163b117A17F3770f5?a=0x0000000000000000000000000000000000000000</a></span></p>
<p><span style="font-size: large;">Once the conversion process is complete, you will be able to view your newly minted SWT on your MyCrypto account as well as in the Terminal.</span></p>

# Can I send ARC from MyEtherWallet directly to the SWT token contract?
<p><span style="font-size: large;">No, to exchange from ARC to SWT you will either need to use the automatic conversion tool or use the instructions provided <a href="https://github.com/swarmcity/sc-token/blob/master/token-exchange-miniwhitepaper.md#2-perform-the-token-exchange-yourself-advanced">here</a> to complete the conversion process manually.</span></p>
<p><span style="font-size: large;">Tokens sent directly to the Swarm City token contract will NOT be converted, and can not be recovered.</span></p>
<p><span style="font-size: large;">DO NOT SEND ANY TOKENS DIRECTLY TO THE SWARM CITY TOKEN CONTRACT.</span></p>
<p><span style="font-size: large;">ARC token burn address:&nbsp;<a href="https://etherscan.io/token/0xAc709FcB44a43c35F0DA4e3163b117A17F3770f5?a=0x0000000000000000000000000000000000000000">https://etherscan.io/token/0xAc709FcB44a43c35F0DA4e3163b117A17F3770f5?a=0x0000000000000000000000000000000000000000</a></span></p>
<p><span style="font-size: large;">Once the conversion process is complete, you will be able to view your newly minted SWT on your MyEtherWallet account as well as in the Terminal.</span></p>

# How do I convert SWT tokens stored a MyCrypto address?
<p><span style="font-size: large;">You will need to import your MyCrypto address in to the Terminal.&nbsp;</span></p>
<ul>
<li><span style="font-size: large;">Go to&nbsp;<a href="https://swarm.city/">https://legacy.swarm.city</a></span></li>
<li><span style="font-size: large;">Select "enter here"</span></li>
<li><span style="font-size: large;">Then select "Create new user"</span></li>
<li><span style="font-size: large;">Choose "Yes, convert my tokens"</span></li>
<li><span style="font-size: large;">Now, select "I have Arcade-tokens in an external wallet"</span></li>
<li><span style="font-size: large;">Enter your private key</span></li>
<li><span style="font-size: large;">Create a password to protect your new Swarm City account, and store it in a safe place.</span></li>
<li><span style="font-size: large;">The system will automatically detect and convert your ARC tokens</span></li>
</ul>
<p><span style="font-size: large;">*Be sure that your wallet holds enough ETH to cover the gas transaction fees, approx. 0.00042 ETH</span></p>
<p><span style="font-size: large;"><span>You will be guided through the token exchange process, which should only take a few minutes to execute. Once done, you can view or transact using SWT on your MyCrypto account as well as in the Swarm City Terminal.</span></span></p>
<div><span><br /></span></div>
<div class="topic-footer">&nbsp;</div>

# How do I convert tokens stored in a MyEtherWallet address?
<p><span style="font-size: large;">You will need to import your MyEtherWallet address in to the Terminal.&nbsp;</span></p>
<ul>
<li><span style="font-size: large;">Go to <a href="https://swarm.city">https://legacy.swarm.city</a></span></li>
<li><span style="font-size: large;">Select "enter here"</span></li>
<li><span style="font-size: large;">Then select "Create new user"</span></li>
<li><span style="font-size: large;">Choose "Yes, convert my tokens"</span></li>
<li><span style="font-size: large;">Now, select "I have Arcade-tokens in an external wallet"</span></li>
<li><span style="font-size: large;">Enter your private key</span></li>
<li><span style="font-size: large;">Create a password to protect your new Swarm City account, and store it in a safe place.</span></li>
<li><span style="font-size: large;">The system will automatically detect and convert your ARC tokens</span></li>
</ul>
<p><span style="font-size: large;">*Be sure that your wallet holds enough ETH to cover the gas transaction fees, approx. 0.00042 ETH</span></p>
<p><span style="font-size: large;">You will be guided through the token exchange process, which should only take a few minutes to execute. Once done, you can view or transact using SWT on your MyEtherWallet account as well as in the Swarm City Terminal.</span></p>


