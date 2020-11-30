# 200 Catalog of Refactoring

***Code Smells***
— What? How can code "smell"??
— Well it doesn't have a nose... but it definitely can stink!

## 100 Bloaters

See [README.md](./100/README.md)

Bloaters are code, methods and classes that have increased to such gargantuan proportions that they are hard to work with. Usually these smells do not crop up right away, rather they accumulate over time as the program evolves (and especially when nobody makes an effort to eradicate them).

- Long Method
- Large Class
- Primitive Obsession
- Long Parameter List
- Data Clumps

## 200 Object-Orientation Abusers

See [README.md](./200/README.md)

All these smells are incomplete or incorrect application of object-oriented programming principles.

- Alternative Classes with Different Interfaces
- Refused Bequest
- Switch Statements
- Temporary Field

## 300 Change Preventers

See [README.md](./300/README.md)

These smells mean that if you need to change something in one place in your code, you have to make many changes in other places too. Program development becomes much more complicated and expensive as a result.

- Divergent Change
- Parallel Inheritance Hierarchies
- Shotgun Surgery

## 400 Dispensables

See [README.md](./400/README.md)

A dispensable is something pointless and unneeded whose absence would make the code cleaner, more efficient and easier to understand.

- Comments
- Duplicate Code
- Data Class
- Dead Code
- Lazy Class
- Speculative Generality

## 500 Couplers

See [README.md](./500/README.md)

All the smells in this group contribute to excessive coupling between classes or show what happens if coupling is replaced by excessive delegation.

- Feature Envy
- Inappropriate Intimacy
- Incomplete Library Class
- Message Chains
- Middle Man
