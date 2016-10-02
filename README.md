# Shopping-cart-demo
Demo shopping website that uses blockonomics payments API, hosted at http://shopping.blockonomics.co 

# Requirements
php, php-sqli and mysql-server   
`sudo apt-get install php php-sqli mysql-server`      

Web server supporting php like nginx, apache. For a simple php server you can run      
`php -S localhost:8000`


# Setup

##Blockonomics merchant setup 
* Complete [merchant wizard](https://www.blockonomics.co/views/merchants_get_started.html), add &lt;your server_url&gt;/shopping-cart-demo/php/callback.php?secret=&lt;your secret&gt; as the callback url
* Obtain api key from Wallet Watcher > Settings

##Server Setup
* Clone the git repository into the ROOT of your web server.
* Change the file *php/config.php* to set your db credentials, blockonomics api key 
* Run your web server
* Navigate to shopping-cart-demo/php/setup.php in your browser (Should show __Database setup is done__)
* Navigate to shopping-cart-demo/index.html in browser and enjoy shopping !

