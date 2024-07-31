// Task1
// function total(a){
//     let x = Object.values(a)
//     return x.length
// }
// console.log(total({ a: "moron", b: "scumbag", c:"moron", d: "dirtbag" }));



// Task3
// function test(number, index){
//     return number >= range.min && number <= index.max
// }
// console.log(test(4, { min: 0, max: 5 }));
    


// Task4
// let test=(obj)=>{
//     let result = Object.values(obj)
//     return result.join(' ') +' '+ obj[2]
// }
// console.log(test({1: "Mommy", 2: "please", 3: "help"}));


// Task5
// let test=(obj,key)=>{
//     for(let keys in obj){
//         if(obj[keys] == obj[key]) return true
//     }
//     return false
// }
// console.log(test({ craves: 'true', midnight: 'true', snack: 'true' }, "morning"));


// Task6
// let test=(obj)=>{
//     let sum = Infinity
//     for(let key in obj){
//         if(obj[key] < sum) sum = obj[key]
//     }
//     return sum
// }
// console.log(test({"cyan": 23,"magenta": 12,"yellow": 10}));



// function test(obj1, obj2) {
//         let keys1 = Object.keys(obj1);
//         let keys2 = Object.keys(obj2);
//         let keys = keys1.filter(key => keys2.includes(key));
//         let result = {};
//         keys.forEach(key => {
//             if (obj1[key]!== obj2[key]) {
//                 result[key] = Math.abs(obj1[key] - obj2[key]);
//             }
//         });
//         return result;
// }
// console.log(test({ "baseball bat": 20 }, 5));


// let  test = (a, b) => {
//         let str = b.split(',');
//         for (let i = 0; i < str.length; i++)  a = a[str[i]]
//         return a;
// }
// console.log(f({ user: { details: { address: { city: "New York" } } } }, "user.details.address.city"));


// function test(...a) {
//         let max = a[0];
//         for (let i = 1; i < a.length; i++) {
//             if (a[i] > max) max = a[i];
//         }
//         return max;
// } console.log(test({ tile: "Z", score: 10 }, { tile: "X", score: 8 }, { tile: "D", score: 2 },));
