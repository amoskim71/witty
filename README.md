# witty

> A prototype E-commerce platform that aims at simulating real-world market like experience and improving customer experience. Made for IndiaHacks 2016.

See it live in action https://bargainhawk.firebaseapp.com/

**For updated source of Android application, refer <https://github.com/brainbreaker/WITTY>**

[![vido_thumbnail](https://c1.staticflickr.com/3/2154/2054140257_58e87296b6.jpg)](https://www.youtube.com/watch?v=bYaUbwPRqmw)

## Update
This project is based on Firebase leagcy version (which is now deprecated) and no longer maintained. Please follow latest documentation on <https://firebase.google.com> to integrate firebase in your application.

For reference, you can take a look at this JSON export of the database: https://github.com/brainbreaker/WITTY/blob/master/bargainkart-export%20(1).json

## Everybody Bargains
Have you ever been to Latin or South America? India? rest of Asia? Africa? Middle East? Bargaining is a vital part of offline commerce mostly everywhere. Integrate it into your online shop as well.

## Engage Customers
When your customer starts bargaining, it's more likely they'll end up buying. They simply get more engaged in each new bid. They won't forget you and come back. You'll see.

## Increase Payout
Happy customers aside, let's have your bank manager happy, too! With bargaining, you simply increase your shop's payout for each product sold. And it's not that you're selling less products. Au contraire.


## Story
It's a long one... hang on!

**To understand the app's concept let's start with a story**

John knows a lot about buying products from the offline retailers, he has a decade worth of experience of shopping quality products, saving a lot of bucks by bargaining with the seller.
He loves to talk to sellers. He is very cautious about where he is spending his money so he asks for every minute details of the product before buying it.
John has also used E-commerce websites loaded with different features, but what he misses in every platform is the interaction and lack of details, also most of the sellers are overseas and have improper contact details so he is afraid of investing money in buying online.
He wants to buy products from online platforms because of the variety they offer. If he is assured about qualtity and details of the product he is willing to spend more bucks for getting a product.

**Now let's see the situation from sellers point of view**

Mark owns a Fashion-Store in a shopping mall. He is renowned for his quality and service in his area. Mark offers discounts and accept bargains to customers to attract customers. Now being confident of his products, he wants to expand his brand. One way would be to buy another shop in nearby area and manage both the shops, but there's lot of overhead and costs involved. Perhaps the easier way around for mark would be to start selling his product nation-wide via an e-commerce site. Now here's the catch, due to lack of communication between him and the customer, He will face two problems:

- He doesn't know the exact price he should set. If he sets a price lower than what users can afford, he'll have to cut his profits. On the other hand , if the prices are high no customer would buy his product and he'll be at loss again.
- He can't attract customers by giving the customized offers, discounts and bargains, customer's interests, trends they are following, styles they like etc.

His problem could easily be solved if we give him access to interact with customer personally and provide them stats and analysis about
They want to interact with their customers personally, they want to know each of their customer's interests, trends they are following, styles they like etc. So the questions that arise for him are  

- Which E-commerce platform is developed enough to provide them the needed interaction with the user? 
- Which of them can provide data like how many of the users have this particular product in their cart?
- Which of their products are attracting the customers?
- Which of their products people are not buying due to high prices?
From the above two perspectives we can see there is still a gap between Retailers and customers which E-commerce has not been able to fulfil properly yet. The idea of bridging this gap of communication led us to the development of application 'Witty'. 
'Witty' is made with the objective of:
- Bridging the gap between retailer and customer 
- Increasing competition between sellers and thereby reducing price.
- Simulating a real world market experience like E-commerce where buyers and sellers will have more flexibility in terms of prices and products.
- Making e-commerce browsing more interactive.
'Witty' is a win-win situation for users and as well as the sellers.

**How will users benefit?**

- Witty has an option of requesting a bargain on each product and chat platform for each product to negotiate with sellers.
- Users can clear all their doubts regarding product from retailer itself before buying.
- Multiple sellers will be there on app, meaning a lot of competition because each seller will react differently to user's bargain requests.
- Chats are recorded and making the returns and refunds easier, users can return the product if it's not like the seller promised.
- More personalized experience.
How will sellers benefit?
- We provide a lot of user insights to the seller so they can improve on that and have an edge over other sellers.
- Disperencies and preference issues like payment methods can be resolved in the chat itself.
- We show them what our users are demanding so that they can update their stock accordingly and earn more.
- They can track their users, like... Which of their products are attracting the customers? How many users have the particular product in their cart. Seller will be able to personally chat with any user!
How do we prevent users from not bargaining all the time?
Basically there are hidden discounts based on the certain criteria for those who are buying directly instead of bargaining. That's why bargaining everytime would not be smart decision.

**Let's see how witty is different from developer's point of view:**
- Everything is realtime , Data is stored as JSON, synced to all connected clients in realtime.
- We have android app and website working out of the box in sync.(bargainhawk.firebaseapp.com)
- Moreover you will still able to buy even if you go offline due to some network problem (not a good 3G connection or while passing through tunnel)'Witty' will store the data for you in queue and will sync them when the network arrives. Our Apps work offline also!
- The website is SPA(Single Page Application) which means no reloading of repetitive stuffs which increases the browsing speed.
- Android App even works offline, you can send messages, add products to the cart, request bargains on the products etc. 

**Features Implemented in this prototype:**

Unique features
- Sepereate Interfaces for users and sellers on both android and web platform.
- We've tried to make it interactive and humorous and certain places by adding dialog boxes and tooltips.
- User's ability to bargain and seller's ability to either reject,accept or offer a deal to the user based on the product which user can either accept or reject.
- Live status of the bargain requests and offers is shown to both the sellers and users and once the bargain request or offer is accepted, prodcut is moved to the cart.

User Insights:
- Seller is able to see product stats like how many users have this particular product in their cart or have bidded on them.
- User can demand for a product and sellers can see user demand stats and add the product in their stock accordingly.
- Every user can chat with every seller for each product. You don't have the constraint like you have to buy that product only then you can chat with the seller, even if you are interested in product you can ask details!
- History of the bids and the chats are recorded and are used to resolve disperancies in future.
- All the above with necessary features of E-commerce like carts, product categories, sorting etc.

## Contributing

All patches Welcome!

## License

GNU GPL v3 - see the [LICENSE](https://github.com/satwikkansal/witty/blob/master/LICENSE) file for details.
