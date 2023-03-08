

### Remember: 
> A *key value pair* is a **property**
>
> A **Method** is a *Function* in an *Object*

In Vs code 060323 7pm PirateFunk is the key   

Vs code 060323 8.46pm the George Object at line 45 is an empty Object with different properties - same for other Objects, so if added Jez, Paisley etc 

In Vs code 060323 line 25 `georgeObject.pirateFunk=function() {` the parenthesis will result in executing the function.  Without the parenthesis will just replicate what's been written in console log

V car example of code - parenthesis

> See 840pm code file
line 40 `return "i bought the car for" + carObject.cost` can be replaced by this.cost as carObject is the parent Object that `cost` lives inside  //relates to line 24 `this.cost = _cost;`   

In js whenever you say `this` you are referring to the Object if it's inside a Method. It won't work in a typical function   
`this` is a keyword - the most important thing in js.  Found in an Method that refers to an Object.   It can do lots and lots of things.  Helps becuase would be time consuming to write out the name of the Object repeatedly   

It can also be used:    
1. in a function = global Object (by that neab top level Object)
2. in an event = refers to the element that received the event

I'm unlikely to use use it for other uses as very top level

#### Classes and Constructors   

I am only learning a small part of Classes, there is lots to know and I will keep learning, so not to worry if I don't know everything   

different Objects, e.g. 5 people who want cars with different properties - if don't use Classes and Constructors end up writing a lot of code - see Vs Code file of 174 lines of code as an example.   

Compare this to Vs Code of 8.46 wherwe its just 46 lines of code  - here the code was reconstructed using Classes   

Classes can have specific types of properties - they are *templates* or *blueprints*   

To create a Class you need to think about its properties e.g. if the Class is 'cars' you'd include   
1. color
2. brand
3. cost

A *constructor* is whe you initiate or call the Class - the Constructor comes into action and does stuff for you.  It's like an engine, it initiaites or is triggered when you use the Class e.g. car in Vs code 

See Vs code 070323 7.34pm for use ofthe Constructor

`this.name = "Honda"` where Honda is the value   

It's a much shorter way of writing code to capture information from the prompts and you would have an **Array** and collect this into a database (DB or db)

See Vs code 070323 8.07pm 

**TASK** 070323

1️⃣  | Create a class for different cateogory (Ex: book, bike, pirates etc)   
2️⃣  | Give some properties to it   
3️⃣  | console.log the details of the class   












