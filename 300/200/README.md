# 200 Object-Orientation Abusers
All these smells are incomplete or incorrect application of object-oriented programming principles.

## 100 Switch Statements
You have a complex switch operator or sequence of if statements.

## 200 Temporary Field
Temporary fields get their values (and thus are needed by objects) only under certain circumstances. Outside of these circumstances, they’re empty.

## 300 Refused Bequest
If a subclass uses only some of the methods and properties inherited from its parents, the hierarchy is off-kilter. The unneeded methods may simply go unused or be redefined and give off exceptions.

## 400 Alternative Classes with Different Interfaces
Two classes perform identical functions but have different method names.
