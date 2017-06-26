<link rel='stylesheet' href='style.css' type='text/css'>
<div id="message">This browser does not support Ethereum apps. Please download either <a href="http://ethereum.org">Mist</a> or <a href="https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en">MetaMask for Chrome</a>.</div>

<div>
<table id="info">
  <tr>
    <th>Balance</th>
    <th>TotalSupply</th>
    <th>Deflation</th>
    <th>Buy Price</th>
    <th>Sell Price*</th>
  </tr>
  <tr>
    <td data-th="Balance">0</td>
    <td data-th="TotalSupply">0</td>
    <td data-th="Deflation">0%</td>
    <td data-th="Buy Price">0</td>
    <td data-th="Sell Price">0</td>
  </tr>
</table>
</div>
<br>
<div >
<span id="balance"></span>
</div>

<div>
<span id="dEth_supply"></span>
</div>

<div>
<span id="Eth_supply"></span>
</div>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Buy')" id="defaultOpen">Buy</button>
  <button class="tablinks" onclick="openCity(event, 'Sell')">Sell</button>
  <button class="tablinks" onclick="openCity(event, 'Transfer')">Transfer</button>
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

<script src="scripts.js"></script>


