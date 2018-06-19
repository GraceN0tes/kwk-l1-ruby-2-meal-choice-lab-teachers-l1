## Hungry? Why Wait? Grab A...
# Here's an example of a 'snacks' method that returns the meal choice passed in to it and defaults to "cheetos" if nothing is passed in.
def snacks(food="Cheetos")
  "Any time, is the right time for #{food}!"
end

# Define breakfast, lunch and dinner methods that return the meal choice passed into them with a default to your favorite.
def breakfast(food="Frosted Flakes")
  "Morning is the best time for #{food}"
end

def lunch(food="grilled cheese")
  "Afternoon is the best time for #{food}"
end

def dinner(food="salmon")
  "Evening is the best time for #{food}"
end



# Call the methods with puts and your own arguments here. Like this:
puts snacks("Swedish fish")


# call your methods here
puts breakfast("Bacon")
puts lunch("turkey sandwich")
puts dinner("steak")

# Call your methods without any arguments here
puts snacks
puts breakfast
puts lunch
puts dinner
<img src="https://s3.amazonaws.com/after-school-assets/snacks.jpg" width="500">

Code your solution in the `meal_choice.rb` file. 

Your job is to define three methods, `breakfast`, `lunch` and `dinner` that take in a food as a string and returns a string stating the appropriate time to eat that food. For example, calling `breakfast("scrambled eggs")` should return something like `"Morning is the best time for scrambled eggs!"`

**Include a default meal_choice** for each method so that if no food is specified, it defaults to the following foods:

- Breakfast should default to **frosted flakes** if no argument is passed in
- Lunch should default to **grilled cheese** if no argument is passed in
- Dinner should default to **salmon** if no argument is passed in


For example, calling `breakfast` with _no argument_ should return `"Morning is the best time for Frosted Flakes!"` Take a look at the example code to get started. 

Call all of your methods (with and without arguments) at the bottom of the file. Then run your program.

## Resources
* [Skorks Blog](http://www.skorks.com/) - [Arguments With Default Value](http://www.skorks.com/2009/08/method-arguments-in-ruby/)
## Resources
* [Learn to Program](http://books.flatironschool.com/books/43?page=72) - [9.1 Method Parameters](http://books.flatironschool.com/books/43?page=72), page 72

<p data-visibility='hidden'>KWK-L1 Hungry? Why Wait? Grab A...</p>
