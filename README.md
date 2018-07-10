#Ruby Cheat Sheet
---
###Variable
A value saved to a specific name
Eg. name = "John"

###Types
String = "" - A string of text
Integer = 1 - A numerical value
Symbols = :name - An immutable object (single reference object)
Object = {} - Something that can contain more data

###Method
A self created process to do something. Can take multiple parameters but not required.
Eg.
def thing(parameter1, parameter2)
    parameter1 + parameter2
end

###Class
An object. Can contain sub methods. Can inherit from other classes
Eg.
class Animal 
    def move(distance)
        puts "Animal walks #{distance}"
    end
end

class Dog < Animal
    def Bark
        puts "WOOF!'
    end
end

###Loops
There are different types of loops:
-FOR
    for i in 1..1000
        puts i if i % 7==0
    end

-EACH
    array = [1,2,3,4,5]

    array.each do |x|
        puts x
    end

-WHILE
    while <conditional> do
        #code
    end

-UNTIL
    until <conditional> do
        #code
    end

###Hashes
Key value pairs. Used for storing data against a specific key
Eg.
{"name" => "age"}

###Arrays
A range of values stored against a single variable name. Arrays can store ANYTHING! Strings, integers, symbols, objects.
E.g
random_array = [1, "hello", :dave, {}]

