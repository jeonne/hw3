Q1: What code draws the blades of grass?

A1: The blades of grass is drawn by the code:

  function draw() {
  stroke(random(60, 70), 100, 90);
  line(x, height-10, x+random(-10, 10), height-10-random(h));
  noStroke();

Q2: What code makes the "lawnmower" come by? How often does it come by?

A2: The "Lawnmower" come by the code:

  if (random(1000) > 999) {
    fill(255);
    rect(0, 0, width, height-15);
    h = 10;
    
  It comes as often as the grass height reaches 10 pixels.

Q3:What's the point of the h variable?

A3: h variable indicates the height of grass. It allows the computer to determine its height and when the "lawnmower" to cut
  the grass off. 

Q4:What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?

A4:The -10 from height-10-random(h) has changed the height of the first batch of grass that starts to grow. It is there to 
  indicate which height the first batch of grass to start with. 
