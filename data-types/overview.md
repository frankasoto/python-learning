# Overview
When writing code, your computer needs to know what kind of information you are working with. This is where data types come into play. Depending on the type of programming language, the data types may be split up a bit differently, especially when dealing with numbers.
In most languages, data types can be grouped into three main categories: Numbers (integers and decimal numbers), Strings (text), and Booleans (true/false values). Now, let’s look at what these mean in the context of Python.

## Numbers
- Numbers are used to represent numerical values and used in many different aspects of programming. Need to count something? Use a number. In python, numbers can be broken down into two different types. Whole numbers like 1, 2, 3... are referred to as integers. Decimals, such as 2.0, 2.1, 2.1234... are referred to as floats.
```
1 + 2      # 3 (adding integers)
2.0 + 2.1  # 4.1 (adding floats)
1 + 2.1    # 3.1 (integer is coerced into a float)

```
* When we say something is coerced, we mean it was changed into a different type. In the above example, the 1 was coerced/became a float so that the calculation would work.
## Strings
- Strings represent text. In Python, you can create a string using either single quotes ' or double quotes ". For example, to say, Hi, my name is John, we would need to wrap the sentence in a double quote to tell the program that we are trying to write a sentence. It would look like:
```
"Hi, my name is John"
'Hi, my name is John'
```

## Booleans
- Booleans are a way to say whether something is true or false. This is especially useful when trying to decide whether a specific section of code should or should not run. For example, a thermostat can be thought of as turning on due to a boolean. If the thermostat is set to 74 degrees for the air, the air conditioner will only turn on if the temperature is greater than 74. So the thermostat checks:
If the thermostat is greater than 74 degrees, turn on. Otherwise, stay off.
```
temperature = 76
temperature > 74   # True
temperature < 74   # False
```