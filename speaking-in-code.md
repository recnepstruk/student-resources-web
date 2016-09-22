# "Speaking in Code" Tips

### Declaring variables and defining primitive, array, object, and function values
> Pattern: declare/define a variable `{ name }` with a `{ type }` value `{ value }`

```javascript

// define a variable `name` with a String value of `Student`
var name = "Student";

// define a variable `zip` with a Number value of `80303`
var zip = 80303;

// define a variable `isOpen` with a Boolean value of `true`
var isOpen = true;

// define a variable `a-r-r` with a value of an empty array (array literal)
var arr = [];

// define a variable `names` as an array of Strings with values 'John', 'Mary', 'Joe', & 'Martha' in title case
var names = ['John','Mary','Joe','Martha'];

// define an array of numbers to a variable named `deposits` with values 102, 406, 321, & 729
var deposits = [102,406,321,729];

// define a variable `o-b-j` with a value of an empty object (object literal)
var obj = {};

// 1. define a variable `user` assigned to an object with properties: name, email, & password
// 2. The values of the properties are: name = 'Jimi', email ='jimi@mail.com', password = 'dragons'
var user = { // 1
    name: 'Jimi',
    email: 'jimi@mail.com',
    password: 'dragons'
}

// 1. define a collection named `library`
// 2. (two ways to says this):
//      i.  the schema for the collection is: title, author, and year
//      ii. the properties of the items in this collection are: title, author, and year
// 3. The first item in the collection has a
//      - name property String value of 'Hamlet'
//      - author property String value of 'Shakespeare'
//      - year property Number value of 1600
//      
//      and so on...
var library = [{ // 1
    title: 'Hamlet', // 2, 3
    author: 'Shakespeare' // 2, 3
    year: 1600
}, {
    title: 'The Lean Startup', // 2, 3
    author: 'Eric Ries', // 2, 3
    year: 2011
}]

// 1. define a variable `anon` with a value of an anonymous function
// 2. within the body of that function, return null;
//
// Another way to say this:
//
// 1. use a function expression to define a variable named `anon` which takes no parameters
// 2. within the body of that function, return null;
//
var anon = function() { // 1
    return null; // 2
}

// 1. define a [named] function `anon` which takes no parameters
// 2. within the body of that function, return null;
function anon() { // 1
    return null; // 2
}

//

```

### Loops
> For Loop Pattern

1. define a for loop using `{ variable name }` as an iterator with an initial value of `{ value }` that is bounded by `{ end condition }` and incrementing/decrementing by `{ value }`
2. within the body of that for loop, `{ code }`

```javascript

// 1. define a for loop using `i` as an iterator with an initial value of `0`, bounded by 10, incrementing by 1
// 2. within the body of that for loop, console.log(i);

for( var i = 0; i < 10; i++ ) {
    console.log( i );
}

```

> While Loop Pattern

1. define a while loop using `{ variable name | expression }` as a condition
2. within the body of the loop, `{ code }`

```javascript

// 1. declare a variable `i` with a value of zero
// 2. define a while loop which uses `i` less than ten as a condition
// 3. within the body of the while loop, increment `i` and then `console.log` its value
//
// Alternative
// 1. define a variable `i` with a value of zero
// 2. define a while loop which exits when `i` has a value of ten
// 3. within the body of the while loop, increment `i` and then `console.log` its value

var i = 0;

while( i < 10 ) {
    i++;
    console.log(i);
}

```

To be continued...
