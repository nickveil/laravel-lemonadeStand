# Laravel Lemonade Stand

A version of the classic video game coded in Laravel.

## Game Play - MVP

[] 1. Default to length of 14days.

[] 2. Game starts on day 1.

[] 3. Each day, the application generates a weather report.

[] 4. Each day, the player chooses how manu of each resource to purchase.

[] 5. When purchases are complete, the application generates a sales report for the day.

[] 6. The sales report is displayed, and the player is promped to continue to the next day.

[] 7. A running total of available resources is kept througout the game.

[] 8. The game ends after day 14 is complete.

[] 9. The application remembers all completed games and lists the ten highest scores.

[] 10. A game's score is the amount of money available after day 14.

[] 11. Standard lemonade recipe
		* 1.75 cups of sugar
		* 24 cups lemon juice (12 lemons)
		* 8 cups water
		* 2 pounds of ice

		Makes 20 servings


		1 cup = 16.tbs

[] 12. Resources:

	* Ice 
		- expires every day
		- sold by the pound
		- cost $0.50
		- makes 10 servings

	* Sugar 
		- carries over to next day
		- sold by the bag (4lbs, approx. 8 cups)
		- cost $2.00
		- makes 16 servings

	* Lemons 
		- carry over to next day
		- sold individually
		- cost $0.10
		- makes 5/6 servings

	* Paper cups 
		- carry over to next day
		- sold pack of 20
		- cost $1.00
		- Makes 20 servings
	* Signs
		 - expire every day
		 - individually made
		 - Cost $0.25

[] 13. Starting money $5.00

[] 14. Weather is given conditions and temperatures

[] 15. Conditions:

	* 5% - Hot and dry - Sales go up 
	* 10% - Hot - Sales go up a little
	* 50% - Sunny - Normal 
	* 10% - Windy - Sales go down a little
	* 10% - Cloudy - Sales go down 
	* 10% - Rainy - Sales go down a lot
	* 5% - Thunderstorms - Sales are non-existant

[] 16. Temperatures: Each condtion has a base temperature which is modified by a 3d6 roll.

	* 90 - Hot and dry
	* 80 - Hot
	* 75 - Sunny
	* 70 - Windy
	* 70 - Cloudy
	* 70 - Rainy
	* 70 - Thunderstorms



[] 17. Conditions and temperature affect sales:
	* Conditions
	* Temperature
	* Number of signs
	* Price

[] 18. Players can't borrow money from mom and dad. Game ends if player is reduced to $0.

[] 19. Provide summary report at end of game.




