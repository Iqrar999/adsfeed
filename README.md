<!doctype html>
<html lang="en"> 
 <head> 
 </head> 
 <body> 
  <header> 
   <h1>BP Coin Ad Watch</h1> 
   <p>Earn BP Coins by Watching Ads!</p> 
  </header> 
  <div class="container"> 
   <div class="wallet"> 
    <h2>Your BP Coin Wallet</h2> 
    <p>Balance: <span id="coin-balance">0</span> BP Coins</p> 
   </div> 
   <div class="ad"> 
    <h2>Ad 1</h2> 
    <p>Watch this ad to earn 5 BP Coins.</p> <button onclick="watchAd(this, 1)">Watch Ad</button> 
   </div> 
   <div class="ad"> 
    <h2>Ad 2</h2> 
    <p>Watch this ad to earn 5 BP Coins.</p> <button onclick="watchAd(this, 2)">Watch Ad</button> 
   </div> 
   <div class="rewards"> 
    <h2>Rewards</h2> 
    <p>Redeem your BP Coins for exciting rewards!</p> <button onclick="alert('Reward redemption is under development!')">View Rewards</button> 
   </div> 
  </div> 
  <footer> 
   <p>© 2025 BP Coin Ad Watch. All Rights Reserved.</p> 
  </footer> 
  <script>
        let coinBalance = 0;

        function watchAd(button, adId) {
            button.disabled = true;
            button.textContent = "Watching...";

            // Simulate ad watching (e.g., a 5-second delay)
            setTimeout(() => {
                coinBalance += 5;
                document.getElementById('coin-balance').textContent = coinBalance;
                button.textContent = "Watched!";
                button.style.backgroundColor = "gray";
                button.style.cursor = "not-allowed";
            }, 5000);
        }
    </script>    
  <h1> Hello </h1> 
  <div>
    This is a html example from Dcoder, 
   <br> have fun. :) 
  </div> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Ad Watching Website</title> 
  <style>
        body { font-family: Arial, sans-serif; text-align: center; margin: 20px; }
        .ad { background-color: #f4f4f4; padding: 20px; margin: 10px; border-radius: 5px; }
        .btn { padding: 10px 20px; background-color: #4CAF50; color: white; border: none; border-radius: 5px; cursor: pointer; }
    </style> 
  <h1>Watch Ads and Earn Coins</h1> 
  <p>Ad Dekhein aur 5 Coins Kamayein!</p> 
  <div class="ad"> 
   <p>Ad 1: Earn 5 Coins</p> <button class="btn" onclick="watchAd()">Watch Ad</button> 
  </div> 
  <p>Wallet: <span id="wallet">0</span> Coins</p> 
  <script>
        let coins = 0;

        function watchAd() {
            alert("Ad Playing...");
            setTimeout(() => {
                coins += 5;
                document.getElementById("wallet").textContent = coins;
                alert("Ad Completed! You earned 5 Coins.");
            }, 5000); // Ad ko 5 seconds ka time diya gaya hai
        }
    </script> 
 </body>
</html># adsfeed
