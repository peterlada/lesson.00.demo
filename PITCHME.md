### Variables, functions, and control structures
#### in Python
##### by Peter Lada

---

### A lesson with many new words.

_Terminology is important so we can communicate with precision._

_It is the first step of the journey of becoming developers._

---

### What is a variable?

A variable is a *name* for a *value*.

*Name* is sometimes called *symbol* or *label*.

*Value* has a *type*.

*Type* can be number, text, a single letter (aka character) or one of many other things. It also can be nothing: *None*

---

### Example

```
foo = 5
```

Yes, like in math when you write *2x + 15 = 45*.

Or when you say *outside temperature is 72 Fahrenheit*

`ouside_temperature_in_F = 72`

---

```
foo = 5
```

Let's break it down:

*foo* is the **name** of the variable.

*5* is the **value**.

In this case the variable's **type** is *number* aka *integer*.
Python figures it out by the fact that we put *5* as the value,
because Python has implicit types.

---

Some actual code:

```
foo = 5
```
this is Python

```
int foo = 5;
```
this is Java, also could be in C

```
let foo = 5;
```
this is Javascript

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

---

### What is a function?

A function is a block of reusable code.

Functions have:
- a *name*
- zero, one or many *parameters* aka *arguments* aka *inputs*
- a *return value* (aka *output*) that might be *None*

Python has many built-in functions and you can also make your own.

---

### Example

```
x = 5
print(x)
```

Prints (to the screen) the value of the variable that is named *x*, which we set to value *5*.

---

### Example

```
def dollar(quarters, dimes):
  return quarters * 0.25 + dimes * 0.10
```

Question to class: _Guess what it does?_

---

```
def dollar(quarters, dimes):
  return quarters * 0.25 + dimes * 0.10
```

Important stuff:
- the `def` keyword, short for definition
- the colon at the end of the definition line
- arguments in parenthesis, separated by comma
- indentation before the `return`
- the `return` keyword

---

```
def dollar(quarters, dimes):
  return quarters * 0.25 + dimes * 0.10
```

Let's break it down:

*dollar* is the **name** of the function.

*quarters* and *dimes* are the two **arguments**.

The return value is calculated from the arguments.

---

Exercise:

Try to write a function (in Python) for:

- _What is a diameter of a circle given the radius?_
- _Guess what_ `round(n)` _does?_
- _What will_ `print(round(5.5))` _outputs?_

---

Solutions:

```
def diameter(radius):
  return 2 * radius
```

---

Solutions cont'd:

- `round(n)` rounds the number n to the nearest integer
- `print(round(5.5))` will print 5 to the screen

---

Now let's run these:

1. open a Terminal
2. type in `python`, hit Enter key
3. type in `print(round(5.5))` (and hit Enter)
4. verify that is printed `5`
5. quit python interpreter with `^D`

---
