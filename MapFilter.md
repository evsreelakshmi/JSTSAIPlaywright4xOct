# JavaScript Arrays, `map()` and `filter()`

## 1. What is an Array?

An **array** is a special type of variable in JavaScript that is used to store **multiple values in a single variable**.

### Example

```javascript
let fruits = ["Apple", "Banana", "Mango"];
```

Here, `fruits` is an array containing three values.

We can access values using their **index**. Array indexing starts from `0`.

```javascript
console.log(fruits[0]); // Apple
console.log(fruits[1]); // Banana
console.log(fruits[2]); // Mango
```

---

## 2. `map()`

The **`map()` method** is used to create a **new array by changing or transforming every element** of an existing array.

### Example

```javascript
let numbers = [1, 2, 3, 4];

let doubled = numbers.map(function(num) {
    return num * 2;
});

console.log(doubled);
```

### Output

```text
[2, 4, 6, 8]
```

Here, `map()` takes each number and multiplies it by `2`.

### Using Arrow Function

```javascript
let numbers = [1, 2, 3, 4];

let doubled = numbers.map(num => num * 2);

console.log(doubled);
```

### Key Point

`map()` is mainly used when you want to **transform every element** of an array.

---

## 3. `filter()`

The **`filter()` method** is used to create a **new array containing only the elements that satisfy a condition**.

### Example

```javascript
let numbers = [1, 2, 3, 4, 5, 6];

let evenNumbers = numbers.filter(num => num % 2 === 0);

console.log(evenNumbers);
```

### Output

```text
[2, 4, 6]
```

Here, `filter()` checks every number and keeps only the numbers that are even.

### Another Example

```javascript
let ages = [12, 18, 25, 15, 30];

let adults = ages.filter(age => age >= 18);

console.log(adults);
```

### Output

```text
[18, 25, 30]
```

### Key Point

`filter()` is mainly used when you want to **select specific elements** based on a condition.

---

## `map()` vs `filter()`

| Method     | Purpose                               | Example                   |
| ---------- | ------------------------------------- | ------------------------- |
| `map()`    | Changes/transforms every element      | `[1, 2, 3]` → `[2, 4, 6]` |
| `filter()` | Selects elements based on a condition | `[1, 2, 3, 4]` → `[2, 4]` |

---

## In Simple Words

* **Array** → Stores multiple values.
* **`map()`** → "Change every item."
* **`filter()`** → "Keep only the items I want."
