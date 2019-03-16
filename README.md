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
- eg: sportman ---- inherite ---- human
- eg: sportfan ---- inherite ---- human

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





## case diagram

## sequence diagram
