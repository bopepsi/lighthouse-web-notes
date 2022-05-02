### Tips
---

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.
<br/>
<br/>

``` javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (!hungry) return `Wait until you are hungry!`;
  if (availableTime > 0 && availableTime < 20) return 'Pick up a snack or grab something you have ready at home.';
  if (availableTime >= 20 && availableTime <= 30) return 'You deserve a break and should take time to cook a tasty meal.';
  if (availableTime > 30) return 'This is an intense program after all and you should probably reconsider.';
};
```