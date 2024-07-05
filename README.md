# javascript-program


# Exercise 1: Let and Const
```
let age=30;
const name="Alice";
 name="bob";
 console.log(name)
```
##Output
![image](https://github.com/vishwaraja21/Javascript-program/assets/102411421/46ff2457-ca12-4241-a4c0-293bf45bba7a)


# Exercise 2: Arrow Functions
```
const add=(a,b)=>{
    console.log(a+b) ;
}
add(4,6);
```
##output
![image](https://github.com/vishwaraja21/Javascript-program/assets/102411421/8e94de6b-eebf-4e98-9ed8-53286d5fec38)


# Exercise 3: Template Literals
```
let name="Alice";
let age=30;
let txt=`Hello,${name} Your age is ${age}.`;
console.log(txt);
```
##output
![image](https://github.com/vishwaraja21/Javascript-program/assets/102411421/f9ac0fb8-eb06-4574-9336-17a5018e47a4)



# Exercise 4: Destructuring Objects
```
const person={
    firstName: "Alice", 
    lastName: "Johnson"
}
const{firstName,lastName}=person;
console.log(firstName);
console.log(lastName)
```
##output
![image](https://github.com/vishwaraja21/Javascript-program/assets/102411421/a360dfb6-d233-4f6d-8216-794fd654768d)


# Exercise 5: Destructuring Arrays
```
const numbers = [1, 2, 3, 4, 5];

const [first, second] = numbers;

console.log(first);  
console.log(second);
```
##output 
![image](https://github.com/vishwaraja21/Javascript-program/assets/102411421/79b8b068-36e7-4b3f-89a6-ebee54a446aa)



# Exercise 6: Spread Operator
```
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];

const combined = [...arr1, ...arr2];

console.log(combined);
```
##output
![image](https://github.com/vishwaraja21/Javascript-program/assets/102411421/12cd6a4f-1523-43c4-b176-66ddbeb65768)


# Exercise 7: Rest Parameters
```
const sum = (...numbers) => numbers.reduce((acc, current) => acc + current, 0);

console.log(sum(1, 2, 3, 4, 5)); 
console.log(sum(10, 20));        
console.log(sum());
```

# Exercise 8: Default Parameters
```
const greet = (name, greeting = "Hello") => `${greeting}, ${name}!`;

console.log(greet("Alice"));          
console.log(greet("Bob", "Hi"));      
console.log(greet("Charlie", "Hey"));
```
##output
![image](https://github.com/vishwaraja21/Javascript-program/assets/102411421/69f53ce3-1caa-41fc-b5db-525489377b72)


# Exercise 9: Classes and Inheritance
```
class Animal {
    constructor(name) {
      this.name = name;
    }
  }
  
  class Dog extends Animal {
    bark() {
      return `Woof! My name is ${this.name}`;
    }
  }
  
  const myDog = new Dog('Buddy');
  console.log(myDog.bark());
```
##output
![image](https://github.com/vishwaraja21/Javascript-program/assets/102411421/5e28bb60-323e-4399-b4f9-f960e0f3d6d6)



# Exercise 10: Promises and Async/Await
```
const waitAndReturn = () => 
    new Promise(resolve => setTimeout(() => resolve("Done"), 2000));
  
  async function run() {
    const result = await waitAndReturn();
    console.log(result); 
  }
  
  run();
```
##output
![image](https://github.com/vishwaraja21/Javascript-program/assets/102411421/e81d90f5-8fee-44de-a91f-c96235946ea2)



























