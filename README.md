<link rel='stylesheet' href='style.css' type='text/css'>
<script src="blockies.js"></script>
<div id="message">This browser does not support Ethereum apps. Please download either <a href="http://ethereum.org">Mist</a> or <a href="https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en">MetaMask for Chrome</a>.</div>

<div>
<a href='https://etherscan.io/address/" + "'><div id='addressicon"' class='icon'></div></a><span id="address">--</span>
</div>

<div>
<table id="info">
  <tr>
    <th>Balance</th>
    <th>TotalSupply</th>
    <th>Ξ Deflation</th>
    <th>Buy Price*</th>
    <th>Sell Price**</th>
  </tr>
  <tr>
    <td data-th="Balance"><span id="balance">-- </span>(Ð)</td>
    <td data-th="TotalSupply"><span id="totalSupply">-- </span>(Ð)</td>
    <td data-th="Deflation"><span id="deflation">-- </span>(%)</td>
    <td data-th="Buy Price"><span id="buyPrice">-- </span>(Ξ/Ð)</td>
    <td data-th="Sell Price"><span id="sellPrice">-- </span>(Ð/Ξ)</td>
  </tr>
</table>
</div>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Buy')" id="defaultOpen">Buy</button>
  <button class="tablinks" onclick="openCity(event, 'Sell')">Sell</button>
  <button class="tablinks" onclick="openCity(event, 'Transfer')">Transfer</button>
  <button class="tablinks" onclick="openCity(event, 'Explorer')">Explorer</button>
</div>

<div id="Buy" class="tabcontent">
 <label for="ethinput"> Amount:</label>
 <input id="Ethinput" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Ξ wei'">
 <button id="buy">Submit</button>
</div>

<div id="Sell" class="tabcontent">
  <label for="dEthinput"> Amount:</label>
  <input id="dEthinput" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Ð wei'">
  <button id="sell">Submit</button>
</div>

<div id="Transfer" class="tabcontent">
<label for="transferAddress"> To:</label>
<input id="transferAddress" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Address'">
<br>
<label for="transferAmount"> Amount:</label>
<input id="transferAmount" onfocus="this.placeholder = ''" onblur="this.placeholder = 'Ð wei'">
<button id="transfer">Submit</button>
</div>

<div id="Explorer" class="tabcontent">
  Coming Soon!
</div>

<script src="scripts.js"></script>


