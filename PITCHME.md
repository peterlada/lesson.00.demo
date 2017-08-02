### Variables, functions, and control structures
#### in Python
### by Peter Lada

---

### What is a variable?

A variable is a *name* for a *value*.

*Name* is sometimes called *symbol* or *label*.

*Value* has a *type*.

*Type* can be number, text, a single letter (aka character) or one of many other things.

---

### Example

`foo = 5`

Yes, like in math when you write *2x + 15 = 45*.

Or when you say *outside temperature is 72 Fahrenheit*

`ouside_temperature_in_F = 72`

---

`foo = 5`

Let's break it down:

*foo* is the **name**.

*5* is the **value**.

In this case the variable's **type** is *number* aka *integer*.
Python figures it out by the fact that we put *5* as the value,
because Python has implicit types.

---

Some actual code:

`foo = 5`  <-- this is Python

`int foo = 5;`  <-- this is Java, also could be in C

`let foo = 5;`  <-- this is Javascript

---

Exercise:

Try to write code (in Python) for these sentences:

- _there are four horsemen_
- _Alice has 4 apples_
- _Bob has 2 more apples than Alice_
- _Cecile has 99 problems_
- _Cecile has one less problem than before_

---

Solutions:

- `horsemen_count = 4  # there are four horsemen`
- `alice_apples = 4  # Alice has 4 apples`
- `bob_apples = alice_apples + 2  # Bob has 2 more apples than Alice`

---

Solutions cont'd:

- `cecile_problems = 99  # Cecile has 99 problems`
- `cecile_problems = cecile_problems - 1  # Cecile has one less problem than before`
