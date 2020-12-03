# 300 Change Preventers
These smells mean that if you need to change something in one place in your code, you have to make many changes in other places too. Program development becomes much more complicated and expensive as a result.

## 100 Divergent Change

See [README.md](./100/README.md)

You find yourself having to change many unrelated methods when you make changes to a class. For example, when adding a new product type you have to change the methods for finding, displaying, and ordering products.

## 200 Shotgun Surgery

See [README.md](./200/README.md)

Making any modifications requires that you make many small changes to many different classes.

## 300 Parallel Inheritance Hierarchies

See [README.md](./300/README.md)

Whenever you create a subclass for a class, you find yourself needing to create a subclass for another class.
