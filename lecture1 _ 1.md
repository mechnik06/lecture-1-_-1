# Hozi shumo hami texta xondesten medonen shumo xela kushish kadagiyen to ki i texta xonen "Ma da shumo ya savet metiym ki dalshi hamixe kushish knen"; 
# Iruz ma da borai zaboni barnomasozii JavaScript kamtar malumot metiym(mediham);
# Iruz ma kati shumo  yak chand chiza megzarem ;
## 1. JavaScript chist?
## 2. Kay va ay tarafi ki paydo shidagiyay?
## 3. Dar borai verebloi javascript?
## 4. Data types?
## 5. Operators?
## 6.Conditions?
## 7.Loops?
## 8.functions?  
# Yakm sar meknem ay xdi Javascript chist?
### JavaScript zaboni barnomasozi meboshad ki sayti mora zinda mekna va zaboni dinamiki meboshad.
# Kay va ay tarafi ki paydo shidagiyay?
### JavaScript soli 1955 ay tarafi Brendan Eich paydo shiday , va vaqte ki hami zabon paydo shidak 10 ruz ba javascript kor kadagiyan va yakm bore ki javascript paydo shid nomi yakmsh " Mocha " bd bad ivaz kardan " LiveScript" vanomi oxironsh JavaScript hast;
# Dar borai verebloi javascript?
### Mo da JavaScript se namud verebl dorem :
### 1.var
``` 
  var cnt = 5;
  console.log(cnt);
```
### 2.let 
``` 
let text = 'name';
console.log(text);
```
### 3.const 
```
const sum = true;
console.log(sum);
```
### Ya chizi diga mo da C++ pesh ay soxtani verebl mo aval type malum mekadem da JavaScript ixeli nest da JavaScript agar verebli mo znachenish chize bosha type hamu meshava.
# Data types?
### Mo da zaboni JavaScript 8 data types dorem ki ba du gyryh judo meshavand.
### PRIMITIVE va OBJECT.
### Da PRIMITIVE doxil meshava.
```
1.String
2.Number
3.Symbol
4.Bigint
5.Undefined
6.Null
7.Boolean
```
### Da OBJECT doxil meshava.
```
1.Object
2.Array
3.Function
```
![Alt-текст](/WSF4GApTZ.avif)
# Condition?
### Condition xdsh chiyay Condition xdsh ysloviya.
### Mo da JavaScript se namud Condition dorem.
### 1.if/else if/else.
```
if(2 == 2){
    console.log(true)
}
else if(2 == 3){
    console.log(false);
}
else{
    console.log("Not found");
}
```
### 2.Ternary operator.
```
  let num= 2 == 2 ? true : 3 == 2 ? false : "Not found";
```
### 3.Switch.
```
let dayOfWeek = new Date().getDay();
let message;
switch (dayOfWeek) {
    case 0:
        message = "Sunday";
        break;
    case 1:
        message = "Monday";
        break;
    case 2:
        message = "Tuesday";
        break;
    case 3:
        message = "Wednesday";
        break;
    case 4:
        message = "Thursday";
        break;
    case 5:
        message = "Friday";
        break;
    case 6:
        message = "Saturday";
        break;
    default:
        message = "Not found day";
}

console.log(message); 
```
# Loops?
### Mo da JavaScript 3 namud loop dorem for , while , Do while.
## 1.For
```
for(let i = 0; i < 10 ; i++) {
    console.log(i);
}
```
## 2.While 
```
let cnt = 0;
let num = 0;
while(cnt < 3){
    cnt++;
    num+=cnt;
}
console.log(num);
```
## 3.Do while
```
let str = '';
let cnt = 0;
do{
    cnt = cnt + 1;
    str = str + cnt;
}while(cnt < 5);
console.log(str);
```
# Functions?
![Alt-текст](/funcsion.jpg)
### Mo da zaboni JavaScript 3 namud Function dorem.
## 1.Function declaration
### Function declaration ay diga functions farq mekna baroi ki nomi function declarationa xdmon memonem Masalan:
```
function get(num1,num2){
    return num1+num2;
}
```
## Yan savol xami xdi function chiyay?
### Function ya blok kodi tayoray ki mo da yajo menavisemsh va da chanjo istifoda mebarem.
## 2.Function Expression. 
### Function expression functione meboshad ki nom nadora mo vayoda nom monda nametonem 🤔 ba nomi vayo chi meshava nomi vayo nomi verebl meshava chixe hozi mefahmonm. Va function expression du namydan Arrow function va anonymous function.
```
// anonymous function.
let cnt = function(parametr){
    return parametr;
}
// arrow function.
let num = function(parametr) => {
    return parametr;
}
```
## 3.An LIFE  (immediately Invoked Function expression);
```
var cnt = "Mumin";
(function(a,b){
    var cnt = "Aby";
    console.log(cnt); })()
    console.log(cnt);
```




