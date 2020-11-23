### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```Javascripting
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true && availableTime < 20) {
    console.log('Ill pick something up and eat it in the lab');
  } else if (hungry === true && availableTime >= 20 && availableTime <= 30) {
    console.log('Ill find a place nearby');
  } else if (hungry === true && availableTime > 30) {
    console.log("I'm in a bootcamp and should get back to work");
  } else if (hungry === false) {
    console.log('Time to get back to work');
  }
};
```