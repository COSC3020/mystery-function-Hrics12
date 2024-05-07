[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/GDPVb20V)
# Mystery Function

What does the `mystery()` function in the following piece of code do? Add your
answer to this markdown file.

```javascript
function mystery(a) {
    if(a.length == 1) return a[0];
    var foo = mystery(a.slice(1, a.length)) 
    if(foo > a[0]) return foo;
    else return a[0];
}
```
The function pulls the higest value from the array. I added these lines to test my theory:

result = mystery([3,8,10]);
console.log(result);

it checks the length of the array if it's equal to 1 and returns the incex of a[0] if true. foo slices the array by checking the first element against the element stored. If foo is greater then a[0] then it returns that variable. If not it returns the first element in the array. 

Help from TA
