# VODSystemFX

App simulates administration of VOD System. Main objects inside are: distributors, users and products (movies, series, streams). Includes GUI written in JavaFX. It was an university project for Objective Programming subject at 2nd year of studies.

### Project desription

Main objects in program are: movies, series, livestreams, users and distributors. Each product has randomize data including picture, title, description, rating etc. Main differences between 3 products type are: movies can be bought when being in the system and watched many times, series can be bought when in the system but watched many times after official realese date, streams can be also bought before but after streaming date they dissapear from the system. Distributor's tasks are: adding new products, negotiating his agreement and changing price of the products. Types of agreements are: getting monthly salary or being paid for each purchase of his product. 
Users are registrating in the system, buying products, watching them and rating. When new user appears he is selecting type of subscription: basic/family/premium (paid once a month, access to all products) or no subscription meaning paying for each product. 

What's more:
- All objects' fields are generated *randomly*
- Each distributor and user is single *thread*
- Save and loading program state uses *serialization*

### Graphics
#### Main control panel:
<img src="https://user-images.githubusercontent.com/48522246/54287279-a31cba00-45a5-11e9-87f3-3ce3be307270.png" width="600">
  

## Running

When running for the first time I recommend to click 'cancel'. Users will be created automaticaly with program start. Distributors must be added manualy ('New Distributor') so they can create products and add them to the system. At least one distributor must exist so you can add products by yourself ('New Product'). You can also add new users ('New User').

By clicking the object on the list you get details about it with possibility to delete the object. Products list can be searched using right panel. Lists can be refreshed using special button but also when hovering the mouse on 1st or 2nd list so it's important to move the cursor actively to be up to date with the system. 

('Subscription Pricing') button opens the window where you can change pricing of monthly subscriptions for users. It's also the way to trigger system bankcrupcy which ends program after 3 months of negative financial flow (worth trying!). On the right side there is field with current account balance.

I recommend to run the program in the compiler to see details of every action in output.

### Built With

* [Java 8.0]
* [JavaFX]
* [JavaFXML]
* [NetBeans IDE 8.2]

### Author

* **Tomasz Jurek** - *Total work* - [tomaszmjurek](https://github.com/tomaszmjurek)
In case of questions or suggestions feel free to contact me at: tomaszmjurek(at)gmail.com
