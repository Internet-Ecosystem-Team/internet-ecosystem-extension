<template>
  <div>

	<center>
	
 	<h2 style="font-size:70px; padding:30px"><strong><u>Browser Extension</u></strong></h2>

 	<br>
 	<h2 style="font-size:30px; padding:30px"><strong>What Does It Do?</strong></h2>
	
   <p style="font-size:20px; padding:30px; width:80%"">This extension is designed to help your online shopping experience - we have currently tuned it to work with Ebay but we plan to add many more companies in the future. Whenever you search for something on Ebay, a number of leaves should appear next to each item's description, this represents how environmentally friendly it is based on how far it travelled. You can also hover over the leaves to learn some interesting facts about how much carbon is actually being emitted to help you visualise the impact of buying the product.</p>

	<br>

	<h2 style="font-size:30px; padding:30px"><strong>How Do I Install It?</strong></h2>
	
   <p style="font-size:20px; padding:30px; width:80%"">1. Download the  compressed file here: https://github.com/Internet-Ecosystem-Team/internet-ecosystem-extension<br>
2. Extract the contents into your desired directory. <br>
3. Open chrome and click the three dots > "More Tools" > "Extensions"<br>
4. Turn on developer mode<br>
5. Click "Load Unpacked" then select the /extension folder within the extracted files<br>
6. The extension is now ready to use!</p>

	<br>

   <h2 style="font-size:30px; padding:30px"><strong>How Does It Work?</strong></h2>

   <p style="font-size:20px; padding:30px; width:80%"">This extension works by calculating the distance between the item's location and you, then estimating how much carbon it will take to transport it. It uses the "Item Location" information given in the description of the product, and finds your location using the geolocation API. After calculating the distance, it finds the most likely transport method and the carbon emitted on average. It also calculates an interesting fact to put this into perspective. The extension updates the page you are viewing with this information so that you can use it to make informed choices.</p>

   <br>
   <br>

   </center>

  </div>
</template>
