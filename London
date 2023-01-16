let x = 0; // Starting position for x
let y = 400; // Starting position for y
let size = 75; 
let a = 520;
let b = 400;



function setup() {
	createCanvas(520, 500);
	frameRate(32); // Slower frame rate
}

function draw() {
	
background('#6699ff');
noStroke();
fill('#006699');
triangle(450,15,465,55,435,55);
fill('#ffcc00');
rect(435,55,30,20);
fill('#006699');
quad(435,75,465,75,475,100,425,100);
fill('#ffcc00');
rect(425,100,50,20);
square(420,120,60);
	
fill('white');
circle(450,150,54);
	
fill('#ffcc00');
	
rect(425,180,50,220);
rect(375,280,50,120);
rect(325,240,50,160);
rect(205,270,150,130);
rect(155,240,50,160);
	
fill('#006699');
quad(385,260,415,260,425,280,375,280);
quad(335,210,365,210,375,240,325,240);
quad(215,250,315,250,325,270,205,270);
quad(165,210,195,210,205,240,155,240);

fill('#ff6666');
rect(80,240,75,160);
	
fill('#33334d');
quad(90,210,145,210,155,240,80,240);
	
fill('#ffa31a');
rect(15,310,65,90);

fill('#33334d');
quad(25,280,70,280,80,310,15,310);

fill('#4d3219');
rect(485,370,4,30);
rect(505,370,4,30);	 
	
fill('#99cc00');
ellipse(487,360,22,35);
fill('#00cc44');
ellipse(507,360,23,40);

fill('#b3b3cc');
rect(0,400,width,100);
	
fill('#3f3f5a');
rect(0,400,width,10);	

fill('white');
for(let posX = 0; posX < 18; posX++){
rect(posX * 30 , 450, 20, 5);
}	

fill('#3333cc');
for(let posX = 0; posX < 2; posX++){
for(let posY = 0; posY < 2; posY++){
rect(posX * 25 + 28, posY * 35 + 320, 15, 20); 
}
  }
	
for(let posX = 0; posX < 3; posX++){
for(let posY = 0; posY < 4; posY++){
rect(posX * 25 + 85, posY * 35 + 250, 15, 20); 
}
  }	
	
fill('#000000');
for(let posX = 0; posX < 3; posX++){
for(let posY = 0; posY < 3; posY++){
rect(posX * 8 + 170, posY * 40 + 250, 3, 30); 
}
  }

stroke('black');
line(450,150,460,140);
line(450,150,450,130);

noStroke();
fill('#000000');
for(let posX = 0; posX < 2; posX++){
for(let posY = 0; posY < 2; posY++){
rect(posX * 8 + 220, posY * 40 + 290, 3, 30); 
}
  }
	
for(let posX = 0; posX < 2; posX++){
for(let posY = 0; posY < 2; posY++){
rect(posX * 8 + 260, posY * 40 + 290, 3, 30); 
}
  }

for(let posX = 0; posX < 2; posX++){
for(let posY = 0; posY < 2; posY++){
rect(posX * 8 + 300, posY * 40 + 290, 3, 30); 
}
  }
	
for(let posX = 0; posX < 3; posX++){
for(let posY = 0; posY < 3; posY++){
rect(posX * 8 + 340, posY * 40 + 250, 3, 30); 
}
  }

for(let posX = 0; posX < 2; posX++){
for(let posY = 0; posY < 2; posY++){
rect(posX * 8 + 395, posY * 40 + 290, 3, 30); 
}
  }
	
for(let posX = 0; posX < 5; posX++){
for(let posY = 0; posY < 5; posY++){
rect(posX * 8 + 432, posY * 42 + 190, 3, 30); 
}
  }
	
for(let posX = 0; posX < 6; posX++){
rect(posX * 8 + 428, 108, 4, 12);
}	

for(let posX = 0; posX < 4; posX++){
rect(posX * 8 + 436, 60, 4, 15);
}	

for(let posX = 0; posX < 8; posX++){
rect(posX * 34 + 168, 380, 15, 20);
}

fill("#ffad33");
circle(150,70,60);
	
redCar(x, y, size);
	
if (x > width + 100) {
    x = 0; // Reset x position 
    y = 400;
  }
  x = x + 5; // Increment x position	
	
	
blueCar(a, b, size);
	
if (a < width-580) {
	  a = 520;
	  b = 400;
}
a = a - 4;
	
}

function redCar(x, y, size){

//red car 
fill("#ff3300");
rect(x+13, y+10, size-16, size/4);
fill("black");
circle(x + 24, y + 32, size / 5);
circle(x + 62, y + 32, size / 5);
fill("#ff3300");
rect(x+29, y-6, size/2.5, size/4.5);

}


function blueCar(x, y, size){

//blue car 
fill("#002266");
rect(x+13, y+66, size-16, size/4);
fill("black");
circle(x + 24, y + 88, size / 5);
circle(x + 62, y + 88, size / 5);
fill("#002266");
rect(x+29, y + 50, size/2.5, size/4.5);

}
