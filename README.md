// 1. Check whether 2 + 3 * 4 equals 14
let calc = 2 + 3 * 4;
console.log("1.", calc === 14);

// 2. Ternary operator: Pass if marks ≥ 40 else Fail
let marks = 35;
let result = marks >= 40 ? "Pass" : "Fail";
console.log("2.", result);

// 3. Pre-increment operator
let num = 5;
++num;
console.log("3.", num);

// 4. Logical AND (&&): Print first falsy value
let a = 10;
let b = 0;       // falsy
let c = "JS";

let andResult = a && b && c;
console.log("4.", andResult);

// 5. Compare null with 0
console.log("5. null == 0 :", null == 0);
console.log("5. null === 0 :", null === 0);
