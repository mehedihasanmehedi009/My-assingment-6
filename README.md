#### Create answer the question-

# (১) What is the difference between var, let, and const?

answer:- var, let, const এর মধ্যে পার্থক্য হলো ঃ

var:
function scope হয়, মানে ফাংশনের ভিতরে কাজ করে। আবার re-declare (আবার ডিক্লেয়ার) করা যায় এবং মান change করা যায়। কিন্তু সমস্যা হলো hoisting আর block scope respect করে না।

let:
block scope হয় ({} এর ভিতরে কাজ করে)।একই ভ্যারিয়েবলকে আবার declare করা যায় না, কিন্তু মান change করা যায়।

const:
এটাও block scope. একবার মান set করলে পরে পরিবর্তন করা যায় না ।

# (২) What is the difference between map(), forEach(), and filter()?

answer:- map(), forEach(), filter() এর মধ্যে পার্থক্য হলো ঃ

map()
নতুন array return করে এবং প্রতিটি element কে modify করে নতুন array তৈরি করে।

forEach()
শুধু loop এর মতো কাজ করে, নতুন array return করে না কিন্তু এটি মূলত element গুলোর উপর কাজ করার জন্য।

filter()
শর্ত অনুযায়ী array থেকে কিছু element ফিল্টার করে নতুন array return করে।

# (৩) What are arrow functions in ES6?

answer :- Arrow Functions (ES6)

Arrow function হলো short syntax function।

function keyword লিখতে হয় না, বরং => ব্যবহার হয়।

this keyword আলাদা behave করে (arrow function এ this parent scope থেকে নেয়)।

Example: const name = () => console.log("Mehedi");
name();
output:Mehedi

#### (৪) How does destructuring assignment work in ES6?

answer:-Destructuring Assignment (ES6)

Destructuring মানে হলো object বা array থেকে ডাটা আলাদা করে বের করা।

array Example:-
const arr = [10, 20];
const [x, y] = arr;

object Example:-
const person = {name: "Mehedi", age: 22};
const {name, age} = person;

#### (5) Explain template literals in ES6. How are they different from string concatenation?

answer:- Template Literals (ES6)

Example:-
const name = "Mehedi";
const age = 22;
console.log(`My name is ${name} and I am ${age} years old.`);

Backtick (`  ${variable}`) দিয়ে value insert করা যায়।

Concatenation এ + বারবার ব্যবহার করতে হয়।

Multiline string খুব সহজ।
