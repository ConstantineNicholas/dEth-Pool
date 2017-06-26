<link rel='stylesheet' href='style.css' type='text/css'>
<script src="blockies.js"></script>
<div id="message">This browser does not support Ethereum apps. Please download either <a href="http://ethereum.org">Mist</a> or <a href="https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en">MetaMask for Chrome</a>.</div>

<div>
<span id="address">--</span>
</div>

<div>
<table id="info">
  <tr>
    <th>Balance</th>
    <th>TotalSupply</th>
    <th>Deflation</th>
    <th>Buy Price*</th>
    <th>Sell Price**</th>
  </tr>
  <tr>
    <td data-th="Balance"><span id="balance">-- (Ð)</span></td>
    <td data-th="TotalSupply"><span id="totalSupply">-- (Ð)</span></td>
    <td data-th="Deflation"><span id="deflation">-- (%)</span></td>
    <td data-th="Buy Price"><span id="buyPrice">-- (Ξ/Ð)</span></td>
    <td data-th="Sell Price"><span id="sellPrice">-- (Ð/Ξ)</span></td>
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
  <input placeholder="enter amount in wei">
  <button id="buy">Submit</button>
</div>

<div id="Sell" class="tabcontent">
  <input placeholder="enter amount in dEth">
  <button id="sell">Submit</button>
</div>

<div id="Transfer" class="tabcontent">
<input placeholder="enter amount in dEth">
<br>
<input placeholder="enter address">
<button id="transfer">Submit</button>
</div>

<div id="Explorer" class="tabcontent">
  Coming Soon!
</div>

<script src="scripts.js"></script>


