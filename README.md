<link rel='stylesheet' href='style.css' type='text/css'>
<div id="message">This browser does not support Ethereum apps. Please download either <a href="http://ethereum.org">Mist</a> or <a href="https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en">MetaMask for Chrome</a>.</div>

<div id="ContentPlaceHolder1_divSummary" class="row">
<div class="col-md-6" style="margin-bottom: -3px">
<table class="table">
<thead>
<tr>
<th colspan="2">
Overview
</th>
</tr>
</thead>
<tbody><tr>
<td>ETH Balance:
</td>
<td>
2,883<b>.</b>845401956526994354 Ether
</td>
</tr>
<tr>
<td>ETH USD Value:
</td>
<td>
$683,875.10 <font size="1" style="position:relative;top:-1px">(@ $237.14/ETH)</font>
</td>
</tr>
<tr id="ContentPlaceHolder1_tr_mined">
<td>Mined:&nbsp;
</td>
<td>
<span title="" rel="tooltip" data-placement="right" data-original-title=" = 79,289.51 ETH mined">14592 blocks and 1736 uncles</span>
</td>
</tr>
<tr>
<td>No Of Transactions:
</td>
<td>
<span title="" rel="tooltip" data-placement="bottom" data-original-title="Normal Transactions">1065320 txns </span>
</td>
</tr>
</tbody></table>
</div>
<div class="col-md-6">
<table class="table">
<tbody><tr>
<td id="ContentPlaceHolder1_td_misc" style="border-top-style: none">
<i class="fa fa-cogs"></i> <b>Misc</b>
</td>
<td style="border-top-style: none">
<span id="ContentPlaceHolder1_qrcodeimg" class="pull-right"> <a id="target" href="#" style="margin-top: -5px" title="Display QR Code"><font color="gray">QRCODE </font><img src="/images/qrcode2.png" style="margin-top: -3px"></a> </span>
</td>
</tr>
<tr>
<td>Address Watch
</td>
<td>
<a id="ContentPlaceHolder1_linkAddtoWatch" title="Address watch not available for this address" class="btn-u btn-brd btn-brd-hover btn-u-default btn-u-xs" style="padding: 0px 4px 0px 4px;">Add To Watch List</a>
</td>
</tr>
</tbody></table>
</div>
</div>
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


