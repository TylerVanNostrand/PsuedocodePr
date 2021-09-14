## Pseudocode for Making a Cup of Coffee

# Creat Variables for Program
    Coffee grounds
    Water
    Coffee Filter
    Coffee Pot
    Coffee machine
    Coffee Cup
    Cream
    Spoon

  # Functionality: I need to make a cup of coffee in order to wake myself up all the way
  Add coffee filter to coffee machine
  Add coffee to filter
  Add water to coffee machine
  Pess start on the coffee machine
  Brew coffee
  Add coffee from coffee pot to coffee cup
    

 # Numbers, Strings, Booleans, Arrays, Functions
 * Coffee Machine
    * Start Button
    * Container for Coffee Filter
    * Water Resevoir
    * Coffee Pot
 * Alarm
    * Beep once coffee has finished brewing

# Start Brewing Program

// Begin Program

INIT ()

User.addsCoffeeFilter(1)
Controller.coffeeFilterReceived(1)

User.addsCoffeeGrounds(>=.25cups)
Controller.coffeeGroundsReceived(>=.25cups)

User.addsWater(>=8oz)
Controller.waterReceived(>=8oz)

User.pressesStartButton(True/False)
Controller.startButtonPressed(True/false)

IF User.pressesStartButton()
    IF StartButton = True
        brewCoffee

// End Program

# Objects
User
      addsCoffeeGrounds (if >= .25cups)
      addsCoffeeFilter  
      adsWater (if >= 8oz)
      pressesStartButton

INIT Function
    CREATE coffeePot
    CREATE waterResevior
    CREATE coffeeFilter
    CREATE coffeeGrounds 
    CREATE Alarm

CoffeeMachine
    INIT