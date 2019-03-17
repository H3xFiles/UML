# UML


## class diagram
![](https://www.tutorialspoint.com/uml/images/uml_class_diagram.jpg)

The purpose of class diagram is to model the static view of an application. Class diagrams are the only diagrams which can be directly mapped with object-oriented languages and thus widely used at the time of construction.</br>
UML diagrams like activity diagram, sequence diagram can only give the sequence flow of the application, however class diagram is a bit different. It is the most popular UML diagram in the coder community.

### The purpose of the class diagram can be summarized as:

- Analysis and design of the static view of an application.

- Describe responsibilities of a system.

- Base for component and deployment diagrams.

- Forward and reverse engineering.

### Attribuses
A significant piece of data containing values that describe each instance of a class. Also called fields, variables, propieties. 
```
-name: string
-id:int
```

### Methods
Methods are actions
```
-setName()
```

### Visibility
- The symbol ```-``` means the field or method is private.
- The symbol ```+``` means the field or method is public.
- The symbol ```~``` means the field or method is available to every class in the same package.
- The symbol ```#``` means the field or method is protected.
   - it means that can be accessed only from the class or subclass

### Type of associations:
![](https://raw.githubusercontent.com/H3xFiles/UML/master/Screenshot%20from%202019-03-17%2015-15-33.png)

#### Dependency 
A dependency implies only that objects of a class can work together; therefore, it is
considered to be the weakest direct relationship that can exist between two classes.
The dependency relationship is often used when you have a class that
is providing a set of general-purpose utility functions, such as in Java’s
regular expression (java.util.regex) and mathematics (java.math)
packages. Classes depend on the java.util.regex and java.math
classes to use the utilities that those classes offer.

#### Association
The associations explains a generic association between these two classes.
- eg: sportman ---- association(play)---- sport
- eg: sportfan ---- association(drink)---- beer

#### Aggregation
The aggregation explains a group of the same objects into an association. 
- eg: sportman ---- aggregate ---- sport team 
- eg: sportfan ---- aggregate ---- sport fan club 

#### Composition
The composition explains an association between a child objects and a parent objects in which the child objects exists
iff the parent exists. The line is denoted with a line ending with a black rhombus
- eg: hotelBathroom ---- composition ---- hotel 
- eg: teamFanClub ---- composition ---- sport team 

#### Inheritance
Subclasses Inherite the attributes from the super class it is denote with an arrow.
- eg: sportman ---- inherite ---- human
- eg: sportfan ---- inherite ---- human





## case diagram

## sequence diagram
