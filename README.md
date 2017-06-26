<link rel='stylesheet' href='style.css' type='text/css'>
<script src="blockies.js"></script>
<div id="message">This browser does not support Ethereum apps. Please download either <a href="http://ethereum.org">Mist</a> or <a href="https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en">MetaMask for Chrome</a>.</div>

<div>
<a href='https://etherscan.io/address/" + "'><div id='addressicon"' class='icon'></div></a><span id="address">--</span>
</div>
<section class="content">
				<h2>Hoshi</h2>
				<span class="input input--hoshi">
					<input class="input__field input__field--hoshi" type="text" id="input-4" />
					<label class="input__label input__label--hoshi input__label--hoshi-color-1" for="input-4">
						<span class="input__label-content input__label-content--hoshi">Name</span>
					</label>
				</span>
				<span class="input input--hoshi">
					<input class="input__field input__field--hoshi" type="text" id="input-5" />
					<label class="input__label input__label--hoshi input__label--hoshi-color-2" for="input-5">
						<span class="input__label-content input__label-content--hoshi">Street</span>
					</label>
				</span>
				<span class="input input--hoshi">
					<input class="input__field input__field--hoshi" type="text" id="input-6" />
					<label class="input__label input__label--hoshi input__label--hoshi-color-3" for="input-6">
						<span class="input__label-content input__label-content--hoshi">Town</span>
					</label>
				</span>
				<p>Inspired by Andrej Radisic's <a href="https://dribbble.com/shots/1785176-Jawbreaker-input-field">Jawbreaker input field</a></p>
			</section>
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


