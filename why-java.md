# why java

## extend from C++ but optimized
- eliminate complicated features like pointers, operator loading, multi-class inheritance and destructors
- add garbage collection for memory management, multi-threaded support, network programing libraries.

##  architecture neutral/platform independent
 - compiled to byte code and use the JVM to translated it on the hosted machine

## object oriented
- can control the visibility of the memebrs and data
- dynamic/late/runtime binding - delays the determination of the code until run-time
- polymorphism - overridden methods can be executed at runtime when the type is fully known
- inheritance feature - "is a"
- composition feature - "has a"
- a (parent) - b,c,d (children) 

## static type
- enforce type check in compile time

## dynamic programming language
- classes are loaded on the fly (runtime? compile time?)
- supports reflection - allow object to be queried and manipulated at runtime
- JVM dynamically execute the low level operations ?
- support inheritance - allow behavior to be altered at runtime

## multi threading
- but not automatic

## distributed computing
- extensive TCP/IP networking facilities
- HTTP libraries

## garbage collection
- serial collector will work parallel to look at heap memory to determine which objects are not in used
