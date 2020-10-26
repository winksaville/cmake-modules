# Helper functions for printing all properties

Provides two functions to print all cmake properties
or all properties of a particular target.
From [this answer](https://stackoverflow.com/a/34292622) for
[this stackoverlow](https://stackoverflow.com/questions/32183975/how-to-print-all-the-properties-of-a-target-in-cmake) question.

# Print all cmake properties
function(print_properties)

# Print all properties of a target
function(print_target_properties tgt)
