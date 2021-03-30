Comparison operators is how software and websites automatically figure out what statements are true and false.


Loops check a condition. Its job is to return true statements over and over again until it hits a false statement. Two examples are:

*FOR* loop

function howMany(selectObject) {
  let numberSelected = 0;
  for (let i = 0; i < selectObject.options.length; i++) {
    if (selectObject.options[i].selected) {
      numberSelected++;
    }
  }
  return numberSelected;
}

*WHILE* loop

let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}
 
 MY name is Kafele Sterling and here's the link to my github page: https://knsterling.github.io/reading-notes/
