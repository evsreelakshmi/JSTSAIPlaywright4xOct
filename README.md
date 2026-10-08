Keywords are reserved or special words that have a predefined meaning in JavaScript, such as let, const, if, else, function, return, class, and for
Example:
```javascript
const userName = "Sree";
```


| Part | Meaning |
|---|---|
| `const` | Keyword |
| `userName` | Identifier |
| `"Sree"` | Value |

---


### Examples

```text
let
const
var
if
else
for
while
function
return
class
new
this
try
catch
throw
async
await
switch
case
break
continue
```

Example:

```javascript
let age = 28;

if (age >= 18) {
    console.log("Adult");
}
```

Here:

- `let` → keyword
- `if` → keyword
- `let` tells JavaScript to declare a variable.
- `if` tells JavaScript to evaluate a condition.

---


# Common JavaScript Keywords

### Variable declaration

```javascript
let
const
var
```

Example:

```javascript
let age = 20;
const country = "India";
```

---

### Conditional statements

```javascript
if
else
switch
case
default
```
---

### Loops

```javascript
for
while
do
break
continue
```
---

### Functions

```javascript
function
return
```

### Classes and objects

```javascript
class
extends
constructor
new
this
super
```
---

### Error handling

```javascript
try
catch
finally
throw
```
---

### Asynchronous programming

```javascript
async
await
```

Rules of Keywords

Keywords have a predefined meaning in JavaScript.

Keywords are part of the language syntax.

Keywords cannot normally be used as ordinary identifiers.

Keywords are defined by the programming language, not by the programmer.

Some reserved words have restrictions depending on the context in which they are used.
---
# Identifiers

An **identifier** is a name given by the programmer to identify a program element.

Identifiers can be used for:

- Variables
- Functions
- Classes
- Function parameters
- Objects/properties in appropriate syntax
- Other declared program elements

Example:

```javascript
let userName = "Sree";
```

Here:

```text
let       → Keyword
userName  → Identifier
"Sree"    → Value
```

---
 Invalid Example

let let = 10;

let is already a keyword, so it cannot be used as an ordinary variable name.
#  Why Do We Need Identifiers?

Identifiers allow us to refer to data and program elements later.

Example:

```javascript
let age = 20;

console.log(age);
```

`age` is the identifier.

When JavaScript executes:

```javascript
console.log(age);
```

it uses the identifier `age` to access the value `20`.


---

