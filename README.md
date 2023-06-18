<!-- ! Whatever you can see near beside you is an object -->

Disadvantage of Procedural Programming:

Procedural Programming is good, but there is some serious issue we face when we create software for real world. Mapping real world objects, data programming seem really hard when hard when it comes to procedural programming like C.

1. Code is not reusable.
2. Large code base is hard to manage.
3. Difficult to tracing & fixing bugs.
4. Data is exposed to whole program.
5. Here, operation's priority is higher than data.
6. Difficult to relate with real world data.

<!-- ! Class is a Blueprint to create multiple Object -->

What is an Object?
=> Combination of Noun, Adjective & Verb.
=> A capsule that can encapsulate data & operation
=> Has some private and public properties
=> Has some function which called methods
=> Is a custom data type
=> An isolate environment for properties & methods

<!-- ! Finding Objects, It's Properties and Methods are the main mechanism of learning Object Oriented Programming -->

<!-- ! Things that are important in OPP -->

<!-- But Object is not everything -->

OPP has four main pillar:

1. Abstraction: Abstraction means hiding the implementation details inside and providing just the necessary API. We never know how it is working, we only know what to do.

2. Encapsulation: The definition of encapsulation is "the action of enclosing something in or as if in a capsule". Encapsulation means that each object in your code should control its own state. State is the current "snapshot" of your object.

3. Inheritance: The ability of crating a new class from an existing class. Inheritance is when an object acquires the property of another object. Inheritance allows a class to acquire the properties and behavior of another class.

4. Polymorphism: polymorphism is derived from 2 Greek words: poly and morphs. The word "poly" means many and "morphs" means forms. So polymorphism means "many forms".

<!-- ! To implement abstraction we need to learn about encapsulation properly. -->

Components of a class:
=> Constructor
=> State(Properties, Attributes)
=> Method
=> Static States
=> Static Methods

For example:

class Person{

    private String name; //state
    public static int key; // static state

    public Person(String name){ // constructor
        this.name = name;
    }

    public String getName(){ // method
        return this.name;
    }

    public static Person create(String name){ // static method
        return new Person(name);
    }

}

<!-- ! Encapsulation means that each object in your code should control its own state. -->

<!-- * True Relationship With Object -->

There are two types of relation in OPP:

1. Is A Relation(Inheritance)
2. Has A Relation(Composition, Aggregation)

Is A Relation(Inheritance)

Inheritance: The ability of crating a new class from an existing class. Inheritance is when an object acquires the property of another object. Inheritance allows a class to acquire the properties and behavior of another class.

PERSON{
Id: int,
Name: String,
Email: String,
Password: String,

    createUser(){}
    forgotPassword(){}

}

STUDENT{
<!-- This properties are common in PERSON Class -->

<!-- Id: int,
Name: String,
Email: String,
Password: String, -->

Subjects: String[],
Fee: Double,

<!-- This Method are common in PERSON Class -->
<!-- createUser(){}
    forgotPassword(){} -->

    result(){}

}

TEACHER{
<!-- This properties are common in PERSON Class -->

<!-- Id: int,
Name: String,
Email: String,
Password: String, -->

Subjects: String,
Salary: Double,

<!-- This Method are common in PERSON Class -->
<!-- createUser(){}
    forgotPassword(){} -->

    takeClass(){}

}
