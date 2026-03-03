# JS

 let age = 25;
let price = 10.99;
 let gpa = 2.1;

// console.log(`You are ${age} years old`);
// console.log(`The price is $${price}`)
// console.log(`Your gpa is: ${gpa}`)


// let firstname = "Bro";
// let FavoriteFood = "Pizza";
// let email = "Bro@Gmail.com";

// console.log(typeof firstname);
// console.log(`Your name is ${firstname}`);
// console.log(`You like ${FavoriteFood}`);
// console.log(`Your email is ${email}`);

// let online = false;
// let forsale = true;
// let isStudent = true;

// console.log(`Bro is online: ${online}`);
// console.log(`Is this car for sale: ${forsale}`);
// console.log(`Enrolled: ${isStudent}`);



// let fullname = "Henry Tick";
// let old = 25;
// let school = true;

// document.getElementById("p1").textContent = `Your name is ${fullname}`
// document.getElementById("p2").textContent =  `You are ${age} years old`;
// document.getElementById("p3").textContent = `Enrolled: ${school}`;

// let students = 30;


// students = students - 1;
// students = students + 1;
//  students = students * 2;
// students = students /2 ;
//students = students ** 2
//let extrastudents = students % 3  

//students += 1;
 //students -= 1;
//students *= 2;
//students /= 2;
//students **= 2;
// students %2;

//console.log(students);

// function happybirthday(username, age){
//     console.log("Happy birthday to you");
//     console.log(`Happy birthday ${username}, ${age} you`);
//     console.log(`Happy birthday dear ${username}`);
//     console.log(`You are ${age}`);

// } 

// happybirthday("Brocode", 25);
// happybirthday("femi", 35);
// happybirthday("henry", 55);
// happybirthday("dejj", 70);
 
// function add(x,y){
//     let result = x + y;
//     return result; 
// }

// let answer = add(2,3);
// console.log(answer);

// function sub(x,y){
//     return x -y;
// } 

// function isEven(number){
//     if(number % 2 === 0){
//         return true;
//     }else {
//         return false;
//     }
// }

// console.log(isEven(12));

// function isEven(number){
//     return number % 2 === 0 ? true : false;
// }

// console.log(isEven(12));

// function isEmail(email){
//     if(email.includes("@")){
//         return true;
//     }else {
//         return false;
//     }
// }

// let fruits = ["apple", "orange", "banana"];

// for(let i = fruits.length; i < fruits.length; i += 2){
//     console.log(fruits[i]);
// }

// const matrix = [[1,2,3],
//                 [4,5,6],
//                 [7,8,9]];
// for (let row of matrix){
//      console.log(row); 
// }

setTimeout(function(){  
    console.log("Hello");
}, 3000);

setTimeout(function() {
    console.log("Goodbye");
}, )
const numbers  = [1,2,3,4,5,6];
const squares = numbers.map(function(element){
    return math.pow(element, 2);

})

const cubes = numbers.map(function(element){
    return Math.pow(element, 3);
});

const evenNums = numbers.filter(function(element){
    return element % 2 === 0;
});

const oddNums = numbers.filter(function(element){
    return element % 2 !== 0;
});

const total = numbers.reduce(function(accumulator, element){
    return accumulator + element;
});

console.log(evenNums);


const studentsoff = ["Spone", "patrick", "femi", "fuud"];
const studentUpper =studentsoff.map(studentUpper);
const studentlower = studentsoff.map(lowerCase);

console.log(studentUpper);

function studentUpper(element){
    return element.toUpperCase();
}

function studentlower(element){
    return element.toLowerCase();
}

const words =["apple", "orange", "Banana"];
const longWords = words.filter(getLongWords);
const shortWords = words.filter(getShortWords);

console.log(shortWords);

function getShortWords(element){
    return element.length > 6;
}

function getLongWords(element){
    return element.length > 6
}
