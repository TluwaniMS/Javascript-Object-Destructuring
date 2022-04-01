# Javascript-Object-Destructuring

* How to access object properties:

```
const person = {
  name: "Thando",
  surname: "Mlambo",
  gender: "Female"
};

const { name, surname } = person;

console.log(`The persons full name is ${name} ${surname}.`);
///Will print:
The persons full name is Thando Mlambo
```
* How to access object properties and assign a new name to them:

```
const person = {
  name: "Thando",
  surname: "Mlambo",
  gender: "Female"
};

const { name: firstName, surname: lastName } = person;

console.log(`The persons full name is ${firstName} ${lastName}.`);
///Will print:
The persons full name is Thando Mlambo
```
* How to access object properties and assign a new name to them and a default parameter:
