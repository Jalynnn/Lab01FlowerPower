# Lab01FlowerPower
Types Warmup Lab

# In the src folder is some code
Review the code provided. Answer the following questions by adding comments to your code! You are free to talk with other students, and seek better understanding to these questions. See below for reminders on types, variables, and input

# Step One
Answer the following questions as comments in your code:
1. Find FlowerPower(String name, int shape, String color, double size). This is called a "class constructor" and we use it whenever we want to make things of type FlowerPower. What does it look like it's doing?
2. What would happen if we called daisy.setName("daffodil")?
3. Why do we call specifically daisy.printInfo() and daisy.getName(), but printInfo() just uses getName()?
4. Where do our "getters" (getName(), getShape(), getSize(), getColor()) get their info, since they don't have any parameters?

# Step Two: Coding: flowerComment()
Find the method `flowerComment()`.
Write the code for flowerComment() so that if the color is green or the size is greater than 6cm, the code returns "What a weird flower!" Otherwise it should return "How pretty!"
For example, if someone calls
```python
flowerFunction() # With the flower FlowerPower("daisy", 2, "white", 2.5), it returns "How pretty!"
flowerFunction() # With the flower FlowerPower("wither rose", 17, "black", 6.52) it returns "What a weird flower!"
```
This method does not take any input, it simply relies on the **class**'s information, so consider using the other methods like getSize().

# Step Three: Test flowerComment()
How do you test code? You simply add the lines to your python file (in the future, you will have test lines in separate files).

As such, we would recommend adding the following just above def main().

```python
print("TESTING", daisy.flowerComment())
print("TESTING", witherRose.flowerComment())
```
Also add your own tests!

# Submitting the Assignment
Make sure to submit the assignment for grading! If you haven't clicked through the canvas link in a while, we would suggest clicking through it again before submitting.

# Reminder on Types
We are focusing on three main types in this class: int, float, and string. Ints are integers, so numbers without decimals. If you turn a decimal number into an int, it will completely cut off the decimal part, leaving only the whole number. Floats are decimal numbers, so they do not cut off the decimal, and leave it as is. Strings are essentially like sentences, words, phrases, or other info stored in "". For example, "dog", "I am", and "3 4" are all strings. 

# Reminder on Variables
Like in math, variables are named placeholders for information. Often, in functions, you will see a lot of variable manipulation like x = y + z, where y and z are placeholders for whatever values we give them somewhere else, like in main. We **assign** values with variables with the = sign, like x = 3. In the special case of function input -- these are called parameters, like dec(3), where the dec() code is written dec(num), the computer understands an **implied** num = 3.

# Reminder on Classes
Java is an object-oriented language, meaning it relies a lot on Classes. In this specific example, our class is FlowerPower. This means that any "instance" of FlowerPower, or variable of type FlowerPower, will have certain information in it and certain methods that it can specially use. For example, daisy is an "instance" for FlowerPower, and because of this, it has a name, shape, size, and color. Also because daisy is a FlowerPower, it can use getName() and printInfo().
