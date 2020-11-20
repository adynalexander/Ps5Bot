# Ps5Bot
This is a Scapler Bot for the Ps5
Installation
Install Node.js
version should be >12.9
Install git
download this project
git clone https://github.com/VVNoodle/PS5bot
Open up a terminal
go to project directory cd /the/project/directory
Install yarn by running npm i -g yarn
Install dependencies by running yarn
Make CLI callable
yarn link
Setup
Run ps5bot. You'll be prompted to fill in required checkout info
ps5bot
Note: Below steps are still TODO
Run scraper ps5bot scrape
you will be asked to select the sites to run the bot. If you don't select anything, it will try to run on all websites.
Bot Configs
Configs are read in config.json file. You can either run ps5bot to generate a config file, or duplicate configTemplate.json, rename to config.json, and fill out the fields.

{
  "firstName": "Qwer",
  "lastName": "Ty",
  "phoneNumber": "8011111111",
  "email": "email@example.com",
  "state": "State",
  "city": "Random City",
  "address": "2353 Running Water Ct.",
  "zipCode": "95054",
  "creditCardNumber": "0101101010101",
  "expirationMonth": "10",
  "expirationYear": "2022",
  "cvv": "000",
  "targetEmail": "email2@example.com",
  "targetPassword": "1312321"
}
Double quotes on text is required
Anything after the // are comments for clarification. Remove them if you try to copy paste this example (including the //).
for Target, make sure you have no carts in your account already
Credit Cards supported
Site	Cards
PlayStation Direct	MasterCard, Visa, Discover
Walmart	MasterCard, Visa, Discover, American Express
Target	MasterCard, Visa, Discover, American Express
Make sure to run this script and keep the terminal open around the time of the schedule

Notes
Make sure not to use a VPN since it will possibly trigger captcha verification.
There's a chance WalMart checkout ask for captcha after entering address. If this is the case, bot will pause. As soon as you complete them, bot will resume.
You need a login for Target. And make sure no existing carts.
PS5bot exists to:

practice web scraping and to
buy a single PS5 for myself
The second point is fair imo since it's pretty much an automated version of constantly clicking refresh to buy stuff.
Also: This is not intended to scalp massive quantities of PS5s. That shit aint cool.
