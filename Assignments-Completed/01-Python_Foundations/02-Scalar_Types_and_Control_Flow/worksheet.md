# 📝 Worksheet: 03 - Scalar Types and Control Flow

Use this worksheet to reinforce your understanding of variables, comparisons, and decision logic.

---

## 🧠 Section 1: Scalar Types

1. What is the output of the following code?

```python
x = 10
print(type(x))
```

`Answer:` ______<class 'int'>_________

2. What scalar type would best represent:
   - A person's name: __str___
   - Their age: ___int__
   - Whether they passed a test: __bool__

---

### ✏️ Task: Type Practice

```python
# Create a variable for each type and print its value and type
# Example: an int, float, str, and bool


--- num = 25
pi = 3.14
name = "Kevin"
is_ready = True

print(num, type(num))
print(pi, type(pi))
print(name, type(name))
print(is_ready, type(is_ready))
```
## 🔁 Section 2: Comparison Operators

3. What does the `!=` operator mean?

`Answer:` _____Not equal to_______

4. What will the following code print?

```python
a = 5
b = 3
print(a < b or b < 10)
```

`Answer:` _______True_________

---

## 🔀 Section 3: Control Flow

5. Write a conditional that prints "Pass" if a grade is >= 70, and "Fail" otherwise.

```python
 #Your code:

grade = 75

if grade >= 70:
    print("Pass")
else:
    print("Fail")
```
6. What does `elif` allow you to do?

Answer:` ____elif allows you to check additional conditions after an if statement without writing a new separate if______

---

### ✏️ Task: Your Turn

Write a program that asks for the weather and prints:
- "Bring sunscreen" if it's sunny
- "Take an umbrella" if it's raining
- "Check the forecast" otherwise
  weather = input("Enter the weather: ")
```
weather = input("Enter the weather: ")

if weather == "sunny":
    print("Bring sunscreen")
elif weather == "raining":
    print("Take an umbrella")
else:
    print("Check the forecast")
```
