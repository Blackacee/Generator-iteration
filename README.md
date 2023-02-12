# Generator-iteration
 
function* range(n) {
 for (let i = 0; i < n; ++i) {
 yield i;
 }
}
// looping
for (let n of range(10)) {
 // n takes on the values 0, 1, ... 9
}
// spread operator
let nums = [...range(3)]; // [0, 1, 2]
let max = Math.max(...range(100)); // 99
