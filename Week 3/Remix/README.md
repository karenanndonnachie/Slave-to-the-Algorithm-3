//Sketch made 31/7/2020 Vinny Portrait
//remixed by Chantel, moving facial features

void setup(){ 
size(500,500); //size of canvas
background(0); //background colour
}

void draw(){
fill(131,54,0);
ellipse(250,100,350,350);
fill(255,100,100);
ellipse(250,150,200,200);
noStroke();
fill(255,100,100);
rect(150,150,200,300);
stroke(0);
fill(255);
ellipse(200,200,50,50);
fill(255);
ellipse(300,200,50,50);

fill(0);
ellipse(200-mouseX/25,200,10,10); // moving left eye
fill(0);
ellipse(300-mouseX/25,200,10,10); // moving right eye
fill(mouseX,mouseY,mouseX+mouseY);
rect(150,160-mouseY/20,100,20); // moving left eyebrow
fill(mouseX,mouseY,mouseX+mouseY);
rect(235,150-mouseY/20,100,20);//moving right eyebrow 

fill(0);
  arc(275, 350-mouseY/20, 150, 150, 0, PI); // moving mouth
  
noStroke();
fill(255,100,100);
ellipse(350,270,100,80);
fill(255,100,100);
ellipse(250,500,400,100);
}

void keyPressed(){
  background(mouseX,mouseY,0); // changing colour of background 
}

![](Screen%Shot%2020-08-07%at%2.26.01%am.png) 

