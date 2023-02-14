# Class 7 Reading Notes

## Domain Modeling
- Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

- A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

## HTML table basics

- A table is a structured set of data made up of rows and columns (tabular data). A table allows you to quickly and easily look up values that indicate some kind of connection between different types of data, for example a person and their age, or a day of the week, or the timetable for a local swimming pool.

- The point of a table is that it is rigid. Information is easily interpreted by making visual associations between row and column headers. Look at the table below for example and find a Jovian gas giant with 62 moons. You can find the answer by associating the relevant row and column headers.

- Using tables for layout rather than CSS layout techniques is a bad idea! The main reasons are as follows: 1) Layout tables reduce accessibility for visually impaired users: screen readers, used by blind people, interpret the tags that exist in an HTML page and read out the contents to the user. Because tables are not the right tool for layout, and the markup is more complex than with CSS layout techniques, the screen readers' output will be confusing to their users. 2) Tables produce tag soup: As mentioned above, table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.  3) Tables are not automatically responsive: When you use proper layout containers their width defaults to 100% of their parent element. Tables on the other hand are sized according to their content by default, so extra measures are needed to get table layout styling to effectively work across a variety of devices.

## JavaScript object basics - Introducing Constructors

- A constructor is just a function called using the new keyword. When you call a constructor, it will: 1) create a new object 2) bind this to the new object, so you can refer to this in your constructor code 3) run the code in the constructor 4) return the new object.

- Constructors, by convention, start with a capital letter and are named for the type of object they create. 

## Object Prototypes Using A Constructor

- So what exactly is prototype in JavaScript? Well, simply put, every function in JavaScript has a prototype property that references an object.

- What if instead of creating a separate object to manage our methods (like we're doing with animalMethods), we just put each of those methods on the Animal function's prototype? Then all we would have to do is instead of using Object.create to delegate to animalMethods, we could use it to delegate to Animal.prototype. We'll call this pattern Prototypal Instantiation.

- Again, prototype is just a property that every function in JavaScript has and it allows us to share methods across all instances of a function. All our functionality is still the same but now instead of having to manage a separate object for all the methods, we can just use another object that comes built into the Animal function itself, Animal.prototype.

### Things I want to know more about

- NOTE: these are a very common front end developer interview questions.

- HTML table advanced features and accessibility — such as captions/summaries and grouping your rows into table head, body and footer sections — as well as looking at the accessibility of tables for visually impaired users.

#### Link to my github portfolio [https://github.com/jenniferlidotson](https://github.com/jenniferlidotson)
