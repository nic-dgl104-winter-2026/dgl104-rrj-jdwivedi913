## 1. Pure Function (JavaScript)
   
```
function calculateTotal(price, tax) {
  return price + (price * tax);
}
```

## 2. Immutability Example (JavaScript)

```
const cart = [10, 20, 30];

const updatedCart = cart.map(item => item + 5);

console.log(cart);        // [10, 20, 30]
console.log(updatedCart); // [15, 25, 35]
```

## 3. Functional Methods (JavaScript)

```
const numbers = [1, 2, 3, 4, 5];

const result = numbers
  .filter(n => n % 2 === 0)
  .map(n => n * 3)
  .reduce((sum, n) => sum + n, 0);

console.log(result);
```

## 4. Python Functional Example

```
numbers = [1, 2, 3, 4, 5]

result = sum(map(lambda x: x * 2, filter(lambda x: x % 2 == 0, numbers)))

print(result)
```

## 5. Declarative vs Imperative

### Imperative Style

```
 let sum = 0;
for (let i = 0; i < numbers.length; i++) {
  if (numbers[i] % 2 === 0) {
    sum += numbers[i] * 2;
  }
} 
```

### Functional Style

```
 const sum = numbers
  .filter(n => n % 2 === 0)
  .map(n => n * 2)
  .reduce((total, n) => total + n, 0);
  ```
  
  