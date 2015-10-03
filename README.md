# Essentials

We covered a good deal of material today.  **Essentials** will give you a quick rundown of the terms and concepts that you should be familair with going into next week.

##General##
+ **XCode**: XCode is the integrated development environmet (IDE) where all iOS developers build their apps. It has a ton of functionality so it takes a long time to master.  One of the main benefits of using XCode is it will help you to see the connection of the design of your app in Main.Storyboard, and the behavior of your app.

##InterfaceBuilder##
+ **InterfaceBuilder**: Means probably what you think it means.  This is the part of XCode that allows you to construct the interface — or what the user of your app sees — in a drag-and-drop, intuitive way.
+ **IBOutlet**: An IBOutlet is a connection between an object on your interface, and your actual code.  It allows you to control or change the property or behavior of a label, image, button, or various other objects that exist in the view of your app.  Do you remember how to create an IBOutlet?  
+ **IBAction**: An IBAction is like an IBOutlet, except it is explicitly meant to create a beahvior, or call a function, upon a certain user interaction.  Can you think of an example of when we would invoke an IBAction?  As an example, and IBAction is created when a user clicks a button that changes the text of a label.

##Swift##
+ **Variables**: The concept of a variable in Swift is the same as it is in other programming languages. A variable serves as a placeholder for a certain value that can change.  For example, can have a variable called 

```Swift
var lyel_age:Int = 62
```
You'll notice that variable declaration is a little different in Swift.  You have to *also declare the variable **data type** * when you delcare your variable.  Why do you think Apple wants you to do this?
Speaking of data types, in Swift, you'll find the same common data types that you've likely seen in other langugages, inclusing *String, Int, Double, and Bool.*  A data type is a way of representing a certain type of data.  
+ **Constants**: Constants are simply variables that do not change.  Can you think of a few examples of constants from science?  How about constants that apply to you?

```Swift
let speed_of_light_miles_per_sec:Int = 186,000 
let your_name:String = "St. Thomas Acquinas"
```

We declare constants the same way we declare variables, except with a **let** instead of **var**.
+ **Operators**: We can do all sorts of things to variables and constants, including all of the basic math operators "+,-,*,%"  One important thing — you can only perform an operation between two variables or constants *if they are the same data type.*  For example

```Swift
var my_apples:Int = 35
var your_apples:Int = 4
var our_apples:Int = my_apples + your_apples
print("\(our_apples)")
```
