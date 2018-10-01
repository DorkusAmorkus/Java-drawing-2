# Java-drawing-2


/* Your name: Elias Han

Date: 9/28/18

Project/assignment name: Java Sketch

Description: A sketch of a smiley face

Credits for code referenced: 
https://processing.org/tutorials/color/ 
https://processing.org/reference/arc_.html
https://processing.org/tutorials/drawing/

uses: 
arc
ellipse
color

*/

PShape arc;
PShape ellipse;

void setup(){
 
size(175,175,P2D);

background(0,0,255);

arc(88.5, 88.5, 80, 80, 0, PI, CHORD);
noStroke();
fill(color(0,0,255));
ellipse(56, 46, 55, 55);
noStroke();
fill(0,0,255);
ellipse(116, 46, 55, 55);
noStroke();
fill(0,0,255);
}

void draw() {
  fill(255,255,255);
  arc(88.5, 88.5, 80, 80, 0, PI, CHORD);
noStroke();

fill(255,0,0);
ellipse(56, 46, 55, 55);
noStroke();

fill(255,0,0);
ellipse(116, 46, 55, 55);
noStroke();    
  }
