# robot-project
First programming 11 assignemnt 
/*Jason Shi
Computer Programming 11 
Block 1-4*/




size(800,600);
background(#40E0D0);
fill(#ffff00);
stroke(#ffff00);
ellipse(650,150,150,150); //sun

fill(0,255,0);
stroke(0,250,0);
rect(0,450,800,250);  //meadow
fill(0,0,255);
stroke(0,0,255);
triangle(0,450,200,130,400,450);
triangle(325,450,630,145,800,450);  //moutains

//robot guy
int x = 100;
int y = 100;
int arms = 50;
fill(169,169,169);
stroke(169,169,169);
ellipse(x+75,x*5,60,60);
fill(0,0,0);
stroke(0,0,0);
rect(x+25,y+205,100,200);

//arm left for robot 1
stroke(105,105,105);//grey outline
ellipse(x+25,y+200,50,50);
ellipse(x,y+225,50,50);
ellipse(x-25,y+250,arms,arms);
ellipse(x-40,y+275,arms,arms);
ellipse(x-55,y+300,arms,arms);

//arm right for robot 1
stroke(105,105,105);//grey outline
ellipse(x+125,y+200,arms,arms);
ellipse(x+145,y+175,arms,arms);
ellipse(x+165,y+150,arms,arms);
ellipse(x+185,y+125,arms,arms);
ellipse(x+200,y+105,arms,arms);

//neck for robot 1
line(x+55,y+205,x+55,y+100);
line(x+65,y+205,x+65,y+100);
line(x+75,y+205,x+75,y+100);
line(x+85,y+205,x+85,y+100);
line(x+95,y+205,x+95,y+100);

//head for robot 1
ellipse(x+75,y+70,125,125);//head
fill(255,255,255);
ellipse(x+95,y+65,40,40);//eye
fill(0,0,0);
ellipse(x+95,y+65,8,8);//pupil
fill(128,128,128);
ellipse(x+120,y+85,5,5);//grey spots
ellipse(x+61,y+60,10,10);
ellipse(x+105,y+35,8,8);
strokeWeight(3);
line(x+137,y+87,x+160,y+97);//line thing
line(x+93,y+8,x+110,y-65);
line(x+45,y+12,x+42,y+5);
//patern on robot 1 chest
fill(255,0,0);
stroke(255,0,0);
rect(x+26,y+235,98,5);//red

fill(255,165,0);
stroke(255,165,0);
rect(x+26,y+245,98,5);//orange

fill(255,255,0);
stroke(255,255,0);
rect(x+26,y+255,98,5);//yellow

fill(0,255,0);
stroke(0,255,0);
rect(x+26,y+265,98,5);//green

fill(0,0,255);
stroke(0,0,255);
rect(x+26,y+275,98,5);//blue

fill(#4b0082);
stroke(#4b0082);
rect(x+26,y+285,98,5);//indigo

fill(148,0,211);
stroke(148,0,211);
rect(x+26,y+295,98,5);//violet

fill(255,0,0);
stroke(255,0,0);
rect(x+26,y+305,98,5);//red

fill(255,165,0);
stroke(255,165,0);
rect(x+26,y+315,98,5);//orange

fill(255,255,0);
stroke(255,255,0);
rect(x+26,y+325,98,5);//yellow

fill(0,255,0);
stroke(0,255,0);
rect(x+26,y+335,98,5);//green

fill(0,0,255);
stroke(0,0,255);
rect(x+26,y+345,98,5);//blue

fill(#4b0082);
stroke(#4b0082);
rect(x+26,y+355,98,5);//indigo

fill(148,0,211);
stroke(148,0,211);
rect(x+26,y+295,98,5);//violet

//robot 2
int w = 100;

fill(255,255,255);
stroke(255,255,255);
rect(450,310,80,150);
fill(69,69,69);
quad(w+390,w+60,w+430,w+210,w+390,w+250,w+350,w+210);
fill(200,0,0);
stroke(200,0,0);
ellipse(475,280,15,15);//eyes
ellipse(505,280,15,15);
