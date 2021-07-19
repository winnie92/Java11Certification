# primitive data types

https://docs.oracle.com/javase/tutorial/java/nutsandbolts/datatypes.html

## declaration

- multiple variables with the same type in one line
- assume: integer value to be int(32 bit), decimal value to be double(64 bit), 'a' to be char, "a" or "abc" to be string
- numers
  - 0L/0l -long, 
  - 0.0f/0.0F -float, 
  - 0x1a(numbers 0 through 9 and the letters A through F) -Hexadecimal(base 16)
  - 0b11010 -binary
  - 0117 -octal
  - 1.234e2 == 1.234*10^2 == 123.4
- "\" can be used to escape some character lke \n, \t, \b, \r, \f, \"
- \u prefix unicode numbers/characters ![image](https://user-images.githubusercontent.com/11585326/123185694-7d5d0b80-d464-11eb-930c-6dadd934291e.png)
- "null" may be assigned to any variable, except variables of primitive types, String ok

## initialization

- primitive type loacl variables(declared within methods) must be initialized before used. 
- but primitive type static variables and instance variables don't need to.
- partial initialization:
  - in if but not in else
  - in swtich but not in default 
  - in while loop that would not be executed

## Narrowing and Widening

- narrowing -- not allowed
- widening -- aloowed, assign a smaller variable to a larger type

## Casting





