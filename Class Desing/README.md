# indie-java-Class-Designe

![Image of KyojinIndie](https://github.com/kyojinindie/indie-java-8/blob/main/kyojinIndie.png)

## Encapsulation

The term encapsulation refers to combining data and associated functions as a single unit.
This means that the methods and fields of the class have to be safe from being modified by other classes that implement them.

## Access modifiers

Access modifiers determine the level of visibility for a java entity(Class,Method, or Field).

### Public

Can be accessed from any other classes regardless of the package bundary.
This means that public modifier is visible from all the other classes.

### Private

Can't be accessed from any other classes.
This means that private modifier is not visible from anyh other classes. 

### Protected and Default

Can be accessed within the package.
This means that protecte identifier is visible only for classes in the same package.
The difference between protected and default is, if a subclass belogns to another package protected members are visible for this class, default members are not

#### Note

A class or Interface cannot be declared as private or protected. Furthermore, member methods or fields of an interface cannot be declared as private or protected.

#### Access modifier and their visibility

Modifier | Same class | subclass inside the package|Subclass outside the package| other class inside the package| Other class outside the package
------------ | -------------
PUBLIC | YES | YES | YES | YES | YES
PRIVATE | YES | NO | NO | NO | NO
PROTECTED | YES | YES | YES | YES | NO
DEFAULT | YES | YES | NO | YES | NO

This is a open source project.

Open source is a development methodology; free software is a social movement.

Happy Hacking :)

