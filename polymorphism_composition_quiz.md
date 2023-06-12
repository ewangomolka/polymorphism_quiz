# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

polymorphism means numerous forms, i.e. many things being changed to take different forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

it means that we take variables, functions or objects and override them to produce something that is using the same function but for a different response.

3. What can we use to implement polymorphism in Java?

we can use interfaces to declare a function and implement it into different classes.

4. How many 'forms' can an object take when using polymorphism?

 it can have many forms, one class can be have many methods. 

5. Give an example of when you could use polymorphism.

you can use polymorphism when describing a car type. i.e. a can can have the function to get the tank to full, but you can use the same method to change 
if the petrol car is "filling up!" or if it is an electric car it can say "charging up!" 



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

composition is a relationship style of OOP similar to inheritance but instead of the car inheriting an engine ("is a"), the car "has an" instance of an engine.

7. When would you use composition? Provide a simple example in Java.

when you are creating a class of vehicle for a car dealership. a Vehicle class would be composed of an engine class, tyre class, a Type class and wheel class.

8. Give a difference between composition and aggregation?

Composition is a way to wrap simple objects or stattypes into a single unit. aggregation differs from ordinary composition in that it does not have an owner.
i.e. in composition a parent owns child entity in aggregation the parent has a child entity.

9. What is/are the advantage(s) of using composition/aggregation?

with these you can use polymorphism and code reuse. you cant change behaviour in inheritance.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

if the parent is destroyed the child objects will also disappear.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
if the parent is destroyed the objects will remain but will not be associated with the original class. it can be reused.