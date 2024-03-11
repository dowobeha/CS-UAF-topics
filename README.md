
What students need to know prior to taking CS 311

# High priority


## Core [types](core/types.md)

- Primitive types
	- integer
	- floating point
	- bool
	- char
- Complex types
	- string
	- [vector](types/vector.md)
	- [tuple](types/tuple.md)
	- [map](types/map.md)
## Nuts and bolts

- [variables](core/variables.md)
- control flow
	- [loops](core/loops.md)
	- [conditionals](core/conditionals.md)
	- [functions](core/functions.md)
		- [pass by value](pass%20by%20value.md)
		- [pass by reference](pass%20by%20reference.md)
		- [returning values](returning%20values.md)
- separation of code
	- [header files](design/header%20files.md) vs [source file](design/source%20file.md)
	- [modules](design/modules.md)

## Object-oriented programming

Students should know how to write and use a class:
- class definition
- [access specifiers](oop/access%20specifiers.md)
	- public
	- protected
	- private
- multiple [constructors](oop/constructors.md)
- [destructors](oop/destructors.md)
- [member data](oop/member%20data.md)
- [const](oop/const%20member%20functions.md) & non-const [member functions](oop/member%20functions.md)
- [static member data](oop/static%20member%20data.md)

## Won't get anywhere else

Some things not covered in CS 311 or covered very little:

- [OOP](design/OOP.md) & OO design, including 
	- [inheritance](oop/inheritance.md)
	- [virtual functions](oop/virtual%20functions.md)
	- [separation of concerns](design/separation%20of%20concerns.md) and OO-style [dependency injection](dependency%20injection.md)
- I/O
	- [Formatted I/O](io/Formatted%20IO.md)
	- [File I/O](io/File%20IO.md)]

# Medium priority

## Multi-file project

Students need to have 
- [written code](design/write%20code), [built](design/compile%20code), and [execute](design/run%20code.md) significant software packages involving
	- classes
	- objects
	- multiple functions
	- multiple code files

## Software design principles

Students should know something about designing software themselves:
- [modularity](design/modularity.md)
- [separation of concerns](design/separation%20of%20concerns.md)
- [cohesiveness](design/cohesiveness.md)

Students should be able to interface:
- interface with software written by someone else &/or
- implement someone else's design. 

## Testing and debugging

Students should have performed 
- basic [testing](design/testing.md)
- basic [debugging](design/debugging.md)

## Accessing data

Students know the basics of 
- storing and accessing datasets 
	- in memory
	- in files


# Low priority

Here are a few things that I cover in detail, without assuming much prior experience. I'm generally happier if students have seen them before, but that is not absolutely required:

- [pointers](types/pointers.md)
- built-in [arrays](types/arrays.md)
- [dynamic memory allocation](core/dynamic%20memory%20allocation.md)
- [templates](oop/generics.md)

# Lowest priority

Some things that I cover in detail, and I think it's fine if students have never seen them before.

- [exceptions](core/exceptions.md) & exception safety
- [RAII](oop/RAII.md) & resource management


