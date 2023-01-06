# Console Finances
An exercise in using fundamental javascript concepts to analyse a financial dataset.

## Description

### Purpose
The purpose of this project was to test my understanding of basic javascript concepts such as loops, if statements, arrays and data types.

Using a given dataset of finances over a period of months, I calculated the following values in javascript and printed them to the console log.

* The total number of months included in the dataset.
* The net total amount of Profit/Losses over the entire period.
* The average of the **changes** in Profit/Losses over the entire period.
  * To do this I had to track the total change in profits from month to month and then find the average of this overall - this required creating a new array that tracked the change in values from month to month, I did this using a for loop and iterated through the initial array, pushing the change in value to a new array. Once I had the new array, I could easily work out the average overall change.

* The greatest increase in profits (date and amount) over the entire period.  
* The greatest decrease in losses (date and amount) over the entire period.
  * To work these out, I had to find a way of looking through the entire array and working out which number was the highest and which was the lowest, through some research and reading some documentation, I ended up using the reduce method to work this out.


[Project Website](https://nailahmukhtar.github.io/Console-Finances).

## Usage
To view this in action, you can navigate to my [Project Website](https://nailahmukhtar.github.io/Console-Finances), inspect the webpage and view the console log.

## Credits
Assignment provided by © 2022 edX Boot Camps LLC

## License
Not Applicable.
