# JS-Programs
## Exercise 1:
### Program:
```
const name = "Alice";
//console.log(age,name);
name="Bob";
console.log(age,name);
```
### Output:
![image](https://github.com/Shobika187/JS-Programs/assets/94508142/e39724e5-90ab-488b-8375-f26d891b65a5)
## Exercise 2:
### Program:
```
function add(a, b) {

    return a + b;
    
    }
    console.log(add(10,20));
    const add = (a, b) => a + b;
    console.log(add(10,20));
```
### Output:
![image](https://github.com/Shobika187/JS-Programs/assets/94508142/f0c56a8b-8c19-4534-a2d9-b058710aaac9)

## Exercise 3:
### Program:
```
    const name = "Alice";
    const age = 30;
    console.log(`Hello, ${name}! Your age is ${age}.`);
```
### Output:
![image](https://github.com/Shobika187/JS-Programs/assets/94508142/66b25692-ca22-48c6-9548-c8bd061ab97b)
## Exercise 4:
### Program:
```
const person = { firstName: "Alice", lastName: "Johnson" };
const { firstName, lastName } = person;
console.log(firstName); 
console.log(lastName);
```
### Output:
![image](https://github.com/Shobika187/JS-Programs/assets/94508142/3479635d-7d6b-4c69-80e0-c93674f19e4c)

## Exercise 5:
### Program:
```
const array = [1, 2, 3, 4, 5];
const [first, second] = array;
console.log(first);  
console.log(second);
```
### Output:
![image](https://github.com/Shobika187/JS-Programs/assets/94508142/553bc596-6a4c-468f-8ecb-735fad896b20)

## Exercise 6:
### Program:
```
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];
const combinedArray = [...arr1, ...arr2];
console.log(combinedArray);

```
### Output:
![image](https://github.com/Shobika187/JS-Programs/assets/94508142/982e1782-c94d-4119-8834-629ec0a6318c)

## Exercise 7:
### Program:
```
const sum = (...numbers) => numbers.reduce((acc, current) => acc + current, 0);
console.log(sum(1,2,3));
console.log(sum(11,22,33,44,55));
```
### Output:
![image](https://github.com/Shobika187/JS-Programs/assets/94508142/c4b02228-847e-4ffd-a4f8-8117660dd7e6)

## Exercise 8:
### Program:
```
const greet = (name, greeting = "Hello") => `${greeting}, ${name}!`;
console.log(greet("Alice")); 
```
### Output:
![image](https://github.com/Shobika187/JS-Programs/assets/94508142/ede71441-4740-4986-ae9e-e484496ced75)

## Exercise 9:
### Program:
```
  class Animal {
    constructor(name) {
      this.name = name;
    }
  }
  
  class Dog extends Animal {
    bark() {
      return `${this.name} says: Woow!`;
    }
  }
  
  
  const myDog = new Dog("Tommy..");
  console.log(myDog.name);  
  console.log(myDog.bark());
```
### Output:
![image](https://github.com/Shobika187/JS-Programs/assets/94508142/574e75bd-3d7b-47b3-9f7e-1f8f41d1833a)

## Exercise 10:
### Program:
```
 const waitAndReturn = () => new Promise(resolve => setTimeout(() => resolve("Done"), 2000));

  async function run() {
  
  const result = await waitAndReturn();
  
  console.log(result);
  
  }
run();

```
### Output:
![image](https://github.com/Shobika187/JS-Programs/assets/94508142/c97c520e-c7c5-4ce5-a01b-2d0bdc65aa56)

