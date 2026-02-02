# Project Description
This project primarily serves to scrape Gundam TCG pricing from TCGPlayer and store it within CSVs for exploration and data warehousing. The overarching goal of this project is to see how pricing fluctuates as the state of the game continues to change with each new release. Actions taken during this project include:
* Data Extraction
* Data Transformation
* Data Loading
* Data Exploration/Analysis

# Technologies Utilized
* Python
  * Requests
  * Pandas
  * Datetime
  * Glob
  * OS
  * matplotlib [to-be-added] 

# Background Information
For those unfamiliar with what Gundam is, it all began with the initial broadcast of the anime "Mobile Suit Gundam" in 1979. "Gundams" are comprised of weapons called mobile suits, which lends itself to the various robot-esq appearances that you'll see in the artwork. Since inception, Gundam has established itself in numerous pieces of media and merchandise, such as:
  * TV Shows
  * Model Kits
  * Books/Manga
  * Clothing
  * Food Collaborations
  * and more....

Bandai Namco (the owner of the Gundam franchise) is popular for taking it's well-known IPs (One Piece, Digimon, Dragon Ball) and turning them into hit trading-card-games (TCG). As such, it was only natural that Gundam had finally gotten it's turn, with the very first product being unveiled and available for preorder during Winter 2024. 

Since launch, the game has featured two types of products to purchase cards:
* Starter Decks (STXX): 50-card decks that focus on one-to-two particular shows
* Booster Packs (GDXX): 130+ cards that range in rarity
<sub> _"xx" = number_ </sub>

As the time of creating this project (January 27th), there have been **8 Starter Decks** and **3 Booster Packs** that have been released, with the latest release being "**Steel Requiem Booster Pack (GD03)**".

# Questions Explored
* "What is the most expensive card(s) currently priced at?"
* "What is the average market price of cards per set?"
* "What is the price gap between different rarities?"
  * "At the highest subset of rarities, what are the price gaps there?"
* "What is the most expensive card by structure deck/booster pack?"
* "What is the most expensive 'color' card by set?"  

# Credit
Thank you to the website [TCGCSV](https://tcgcsv.com/)! 

TCGPlayer is not giving out API keys at the moment and have some restrictions on webscraping their product display pages (PDPs). TCGCSV works as a middle man, allowing me to scrape from their website instead and parse the pricing data that I would typically receive from TCGPlayer.
