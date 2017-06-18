<link rel='stylesheet' href='style.css' type='text/css'>
<div id="message">This browser does not support Ethereum apps. Please download either <a href="http://ethereum.org">Mist</a> or <a href="https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en">MetaMask for Chrome</a></div>

<div>
<span id="dEthDay"></span>
</div>

<div>
<span id="dEth_supply"></span>
</div>

<div >
<span id="balance"></span>
</div>

<div id="tabs-container" style="padding: 15px;">
		    	<ul class="tabs-menu">
				<li class="current"><a href="#tab-1">Deflate</a></li>
				<li><a href="#tab-2">Inflate</a></li>
				<li><a href="#tab-3">Transfer</a></li>
				<li><a href="#tab-4">Explorer</a></li>
		   	 </ul>
			<div class="tab">
        	 <div id="tab-1" class="tab-content" style="display: table;">
		 <button id="deflate">Deflate</button><input type="number">
           </div>
           <div id="tab-2" class="tab-content">
	   <button id="inflate">Inflate</button><input type="number">
           </div>
          <div id="tab-3" class="tab-content">
	  <button id="transfer">Transfer</button><input type="number">
          </div> 
          <div id="tab-4" class="tab-content">  	
          </div> 
      </div>

<script src="scripts.js"></script>

<script> 
$(document).ready(function() {
    $(".tabs-menu a").click(function(event) {
        event.preventDefault();
        $(this).parent().addClass("current");
        $(this).parent().siblings().removeClass("current");
        var tab = $(this).attr("href");
        $(".tab-content").not(tab).css("display", "none");
        $(tab).fadeIn();
    });
});
</script>
