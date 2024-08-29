1
function setup() {
2
  createCanvas(600, 600);
3
   background("white");
4
}
5
​
6
​
7
function draw() {
8
  
9
  stroke ("blue");
10
  fill ("red");
11
 
12
  
13
  // console.log(mouseIsPressed);
14
  
15
  if (mouseIsPressed){
16
    rect(mouseX, mouseY, 20, 35);
17
  }
18
}
