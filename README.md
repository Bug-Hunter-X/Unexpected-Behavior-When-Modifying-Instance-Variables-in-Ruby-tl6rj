# Unexpected Instance Variable Modification in Ruby

This repository demonstrates a common pitfall in Ruby where attempting to modify instance variables directly from outside the class doesn't work as expected, unless an explicit setter method is defined.

The `bug.rb` file showcases the problem: assigning a new value to the `@value` instance variable fails to update the object's state.

The `bugSolution.rb` file provides a corrected version by adding a `value=` setter method, enabling the modification of the instance variable.