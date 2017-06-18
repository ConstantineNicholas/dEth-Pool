<link rel='stylesheet' href='style.css' type='text/css'>
<div id="message">This browser does not support Ethereum apps. Please download either <a href="http://ethereum.org">Mist</a> or <a href="https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en">MetaMask for Chrome</a></div>


<div>
<span id="Eth_supply"></span>
</div>
<div>
<span id='dEthDay'>---d --h --m --s</span>
</div>
<div>
<span id="dEth_supply"></span>
</div>

<div >
<span id="balance"></span>
</div>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Deflate')" id="defaultOpen">Deflate</button>
  <button class="tablinks" onclick="openCity(event, 'Inflate')">Inflate</button>
  <button class="tablinks" onclick="openCity(event, 'Transfer')">Transfer</button>
</div>

<div id="Deflate" class="tabcontent">
  <input placeholder="enter amount in wei"><button id="deflate">Submit</button>
</div>

<div id="Inflate" class="tabcontent">
  <input placeholder="enter amount in wei"><button id="inflate">Submit</button>
</div>

<div id="Transfer" class="tabcontent">
<input placeholder="enter amount in wei"><button id="transfer">Submit</button>
</div>

<script src="scripts.js"></script>


