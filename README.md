# Array-2// const superheroes = [

// {name: "Batman", alter_ego: "Bruce Wayne"},
// {name: "Superman", alter_ego: "Clark Kent"},
// {name: "Spiderman", alter_ego: "Peter Parker"}]

// function zoek(spider){
// return spider.name === "Spiderman";
// }

// console.log(superheroes.find(zoek));

// // console.log(superheroes[2]);
// // // function findSpiderMan()
// // // console.log(superheroes[2]);
// **************\***************
// function myFunction(num) {
// return num \* 2;
// }
// var numbers = [65, 44, 12, 4];
// var newarray = numbers.map(myFunction)
// console.log(newarray);

// const rij = [1,4,3,5,6,11]

// function istien(num1){
// { for (num2 in rij)
// if (10 <= num2) {
// return true;
// } else {
// return false;
// } }
// }

// console.log(myfunction);
// const isItalyInTheGreat7 = ['Canada', 'France','Germany','Italy','Japan','United Kingdom','United States']
// for (land of isItalyInTheGreat7) {
// if(land === 'Italy')
// {console.log("true")}}

// console.log;

// var numbers = [65, 44, 12, 4];

// numbers.forEach((num) => {
// console.log(num \* 10);
// // })
// array = [1, 81, 4, 53, 3, 6, 79, 2, 43, 7, 28, 101, 11, 77, 84, 98 ]
// const minderDan = array.some((num)=>{
// return num>=100
// })

// console.log(minderDan);
// // result should be: false

// // result should be 1118
// bigArray = [1, 81, 4, 53, 3, 6, 79, 2, 43, 7, 28, 11, 77, 84, 98, 101, 206, 234]

// function myFunction() {
// bigArray.reduce(optellen, 0);
// }
// function optellen(total, num) {
// return total + num;
// }

// console.log(myFunction);

const euros = [1, 81, 4, 53, 3, 6, 79, 2, 43, 7, 28, 11, 77, 84, 98, 101, 206, 234];

const sum = euros.reduce((total, amount) => total + amount);

console.log(sum);
