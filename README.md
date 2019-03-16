# UML


## class diagram

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

#### Inheritance
Subclasses Inherite the attributes from the super class it is denote with an arrow.
- eg: sportman<sub class> ---- inherite ---- human<super class>
- eg: sportfan<sub class> ---- inherite ---- human<super class>

#### Association
The associations explains a generic association between these two classes.
- eg: sportman<sub class> ---- association(play)---- sport<sub class>
- eg: sportfan<sub class> ---- association(drink)---- beer<sub class>

#### Aggregation
The aggregation explains a group of the same objects into an association. 
- eg: sportman<sub class> ---- aggregate ---- sport team <sub class>
- eg: sportfan<sub class> ---- aggregate ---- sport fan club <sub class>

#### Composition
The composition explains an association between a child objects and a parent objects in which the child objects exists
iff the parent exists. The line is denoted with a line ending with a black rhombus
eg: hotelBathroom<sub class> ---- composition ---- hotel <sub class>
eg: teamFanClub<sub class> ---- composition ---- sport team <sub class>





## case diagram

## sequence diagram
