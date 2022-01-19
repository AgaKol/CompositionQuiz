# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

The condition of occuring in many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

Polymorphism is the ability of an object to take on many forms. This means any child class object can take any form of a class in its parent hierarchy and of course itself as well.

3. What can we use to implement polymorphism in Java?

We can use interfaces or inheritance.

4. How many 'forms' can an object take when using polymorphism?

As many as needed.

5. Give an example of when you could use polymorphism.

The reason why you use polymorphism is when you build generic frameworks that take a whole bunch of different objects with the same interface. When you create a new type of object, you don't need to change the framework to accommodate the new object type, as long as it follows the "rules" of the object.



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

With composition we see objects as "being part of" another object - a class can composed of objects of other classes.

7. When would you use composition? Provide a simple example in Java.

You would use composition when you have an object composed of other objects, for example class House composed of Roof, Doors, etc.

8. Give a difference between composition and aggregation?

Using composition, when an object in destroyed, it also destroys all objects it's composed of. Using aggregation, when an object is destroyed, the objects it's composed of do not get destroyed as they exist independently.

9. What is/are the advantage(s) of using composition/aggregation?

Less risk for the code to get messy than with inheritance, easier to change and update it.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

All the objects get destroyed.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

Objects exist independently.