# Super Mario Stairs

Super Mario Bros. (1985) is arguably the most iconic videogame of all time.

Even though the game has 32 levels, many speedrunners can beat the entire thing in under five minutes.

However, even the most accomplished speedrunners can have their runs foiled by a run in with the dreaded stairs:

![SMB1 Stairs](smbstairs.png)

One wrong move on these steps, and your momentum is gone, and with it, any chance of a world-record time.

## The Goal

We're going to write three methods: one to build downward stairs, one to build upward stairs, and one to build pyramid stairs (they go up and then go down).

Here's what your code should ultimately be able to do:

#### Code for descending stairs:

```ruby
downstairs(4)
```

The code above should print a descending staircase of four steps to the console like this:

```bash
#
##
###
####
```

#### Code for ascending stairs:

```ruby
upstairs(6)
```

The code above should print an ascending staircase of six steps to the console like this:

```bash
     #
    ##
   ###
  ####
 #####
######
```

#### Code for pyramid stairs:

```ruby
pyramid(4)
```

The code above should print an ascending staircase of 4 steps and it's mirror descending staircase to the console like this:

```bash
   # #
  ## ##
 ### ###
#### ####
```

## Skills You May Need

### Print v. puts

In Ruby, it's important to realize there are many ways to print information to the console. The puts method creates a new line, places the string on that line, and then moves to a new line before it does the next thing.

The print method simply puts the string on the console in the existing line without dealing with new lines at all.

Here are some examples:

```ruby
puts "Welcome user!"
puts "This is a puts statement."

print "This is a print statement"
print "This is another print statement"
```

The code above will print to the console like this:

```bash
Welcome user!
This is a puts statement.
This is a print statementThis is another print statement.
```

Print and puts format differently on the console, so try both and see if you can find a way to use them to make the console operate the way you want.

### For-in loops

Doing this will be a little repetitive. You may want a way to loop through code.

One of the most precise ways of doing this is with a for-in loop. Feel free to catch a refresher of that concept from our <a href="https://github.com/upperlinecode/intro-se-1-methods-leap-year#for-in-loops">leap year lab</a>.

### Times loops

Ruby has this magnificent style of iteration called "times", and it's special because it reads like plain English.

Here's what a times loop might look like:

```ruby
5.times do
  puts "Hello!"
end
```

The code above will run the internal codeblock 5 times, so it makes sense that the output would look like this:

```ruby
"Hello!"
"Hello!"
"Hello!"
"Hello!"
"Hello!"
```
