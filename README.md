# JavaScript-Tutorial By Rituraj Mahato

1️⃣ Ways to print in JavaScript - <br><br> 
✅ console.log("Hello World"); <br>
✅ alert("Hi There"); <br>
✅ document.write("This is my document"); <br>
<br>
2️⃣ JavaScript Console API - <br><br> 
✅ console.log("Hello World", 5 + 5, "Another log"); <br>
✅ console.warn("This is a warning"); <br>
✅ console.error("This is an error"); <br>
<br>
3️⃣ What are Variables? - Containers to store data values <br><br> 
✅ Addition <br>
<br>
⏩ var num1 = 35; <br>
⏩ var num2 = 55; <br>
⏩ console.log("Addition of num1 and num2 will give:", num1 + num2); <br>
<br>
4️⃣ Datatypes in JavaScript - <br><br>
✅ String <br>
<br>
⏩ var str1 = "This is a string"; <br>
⏩ var str2 = 'This is a string'; <br>
<br>
✅ Numbers <br>
<br>
⏩ var num1 = 36.42; <br>
⏩ var num2 = 412;<br>
<br>
✅ Arrays <br>
<br>
⏩ var arr = [1,2,3,4,5]; <br>
⏩ console.log(arr[0]); will give 1 <br>
⏩ console.log(arr[1]); will give 2 <br>
<br>
✅ Objects <br>
<br>
⏩ var marks = {Rituraj: 82, Shyam: 68, Max: 75}; <br>
⏩ console.log(marks); <br>
<br>
✅ Booleans <br>
<br>
⏩ var a = true; <br>
⏩ var b = false; <br>
⏩ console.log(a,b); <br>
<br>
✅ undefined <br>
<br>
⏩ var notDefined = undefined; <br>
⏩ console.log(notDefined); <br>
<br>
✅ null <br>
<br>
⏩ var emptyHere = null; <br>
⏩ console.log(emptyHere); <br>
<br>
📍 There are two types of data types in JavaScript - <br>
<br>
🎯 Primitive data type - undefined, null, number, string, boolean, symbol <br>
🎯 Reference data type - arrays and object <br>
<br>
5️⃣ Operators in JavaScript - <br>
<br>
✅ Arithmetic Operators <br>
<br>
⏩ var a = 100; <br>
⏩ var b = 20; <br>
⏩ console.log("Addition of a and b is ", a + b); <br>
⏩ console.log("Subtraction of a and b is ", a - b); <br>
⏩ console.log("Multiplication of a and b is ", a * b); <br>
⏩ console.log("Division of a and b is ", a / b); <br>
<br>
✅ Assignment Operators <br>
<br>
⏩ var c = b; <br>
⏩ c += 5; <br>
⏩ console.log(c); will give 25 <br>
<br>
✅ Comparision Operators <br>
<br>
⏩var x = 35; <br>
⏩var y = 55; <br>
⏩console.log(x == y); will give false <br>
⏩console.log(x >= y); will give false <br>
⏩console.log(x <= y); will give true <br>
⏩console.log(x > y); will give false <br>
⏩console.log(x < y); will give true <br>
<br>
✅ Logical Operators <br>
<br>
🎯 Logical AND <br>
<br>
⏩console.log(true && true); will give true <br>
⏩console.log(true && false); will give false <br>
⏩console.log(false && true); will give false <br>
⏩console.log(false && false); will give false <br>
<br>
🎯 Logical OR <br>
<br>
⏩console.log(true || true); will give true <br>
⏩console.log(true || false); will give true <br>
⏩console.log(false || true); will give true <br>
⏩console.log(false || false); will give false <br>
<br>
🎯 Logical NOT <br>
<br>
⏩console.log(!false); will give true <br>
⏩console.log(!true); will give false <br>

6️⃣ Functions in JavaScript - <br>

📍 Functions are used to create DRY code - It means don't repeat yourself. <br>
<br>
✅ Average of two numbers. <br>

⏩ function avg(a,b){
    c = (a + b)/2;
    return c;
 } <br>
⏩ av1 = avg(2, 4); <br>
⏩ av2 = avg(6, 4); <br>
⏩ console.log(av1, av2); will give 3 and 5 <br>

7️⃣ Conditionals in JavaScript - <br>

✅ if and else statements <br> <br>
⏩ var age = 20; <br>
⏩ if (age > 18){
    console.log("You can drink alcohol");
} <br> else {
    console.log("You can't drink alcohol");
}

