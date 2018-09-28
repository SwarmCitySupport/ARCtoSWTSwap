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
