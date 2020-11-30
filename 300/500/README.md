# 500 Couplers
All the smells in this group contribute to excessive coupling between classes or show what happens if coupling is replaced by excessive delegation.

## 100 Feature Envy
A method accesses the data of another object more than its own data.

## 200 Inappropriate Intimacy
One class uses the internal fields and methods of another class.

## 300 Message Chains
In code you see a series of calls resembling $a->b()->c()->d()

## 400 Middle Man
If a class performs only one action, delegating work to another class, why does it exist at all?
