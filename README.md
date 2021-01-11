# Amazon-Price-Alert


Getting Amazon Price Drop alert using this Python script


Python does amazing things. 
Just imagine, you want to buy a new iPhone. You are sick of checking Amazon website again and again. But, it’s price isn’t dropping and you always get disappointed.
What if, there is an automatic price checker that will give you an email alert if there is a price drop. Exciting, isn’t it? Let’s do the same by writing a Python script.


##How to use
-Simply copy the link of the product and your budget that's it!
-Paste the link when the program requests you to
-Enter budget for the product(without currency symbol)
-Select frequency to check prices
-Keep the script running in the background The scraper will do the rest for you and notify you when the price is in your budget. However, it is to be kept in mind that the sender   email ID and password has been stored in os variables in the script. Therefore, wherever you see the imports of 'DEVELOPER_EMAIL' and 'DEVELOPER_PASS', be sure to replace them   
  with the email ID you wish to recieve the notification from.


##Modules used (available in requirements.txt)
-requests_html
-BeautifulSoup
