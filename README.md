![chick](https://github.com/user-attachments/assets/cd57996c-7b2d-4028-a180-4a5b46947c86)

Virtual Pet
=============
/*
Yailyn Cera 
08/16/24
creating/combining shapes to form an animal using code 
*/

import processing.core.PApplet;

public class Sketch extends PApplet {

  public void settings() {
    size(1000,1000); // to make canvas larger change size width and length
  }

  public void setup() {
   
  }

  public void draw() {
    background(93, 115, 105);
    fill(32);
    triangle(170,320,290,225,298,368);//foundational background dark part of ears 
    triangle(530,320,420,225,402,368);
  
    
    fill(55);
  triangle(350,200,290,270,410,270);//trunk top 
    triangle(290,270,410,270,350,350);
    triangle(290,270,350,350,300,395);
    triangle(410,270,350,350,400,395);
    triangle(350,350,300,395,400,395);
    
    fill(32);
    quad(370,505,361,525,346,533,336,529);//bottom hanging of trunk
    quad(336,529,318,511,318,497,363,512);
    fill(5);
    triangle(318,511,326,462,341,502);
    
    fill(50);
    triangle(300,395,400,395,350,430);//bottom trunk
    triangle(300,395,350,430,325,475);
    triangle(400,395,350,430,375,475);
    quad(350,430,325,475,350,510,375,475);
    triangle(325,475,350,510,330,505);
    triangle (375,475,350,510,370,505);
    triangle (330,505,370,505,350,525);
   
    
    quad(350,200,290,150,350,110,410,150);//beginning of forehead
    quad(350,200,410,150,450,205,410,270);
    quad(350,200,290,270,250,205,290,150);
   
    triangle(410,270,430,240,435,270);//eye hood 
    
    triangle(435,270,408,302,410,270);
   fill(150);//eye color
    triangle(410,270,420,280,435,270);
    fill(55);
    triangle (409,295,430,320,404,355);//tusks beginning
    fill(40);
    triangle(395,115,500,120,455,175);//very top beggining right ear 
    triangle(500,120,455,175,610,175);//right ear continued
    quad(455,175,610,175,585,260,450,210);
    quad(450,208,430,240,530,320,585,260); //middle right ear    
    
    fill(55);
    quad(350,110,395,115,433,135,410,150);//top of head right side 
    quad(433,135,410,150,450,207,455,175);
    fill(150);//tusk right side 
    quad(413,345,424,330,455,360,455,380);
    
    fill(40);//beginning/top of left ear
    triangle(305,115,200,120,245,175);
    triangle(200,120,245,175,110,175);
    quad(245,175,110,175,115,260,250,210);
    quad(250,207,270,240,170,320,115,260);//bottom of middle left ear
    
    fill(55);
    quad(350,110,305,115,265,135,290,150);//top of head left side
    quad(265,135,290,150,250,207,245,175);

    triangle(290,270,270,240,265,270);//left eye hood 
    triangle(265,270,290,270,292,302);
    fill(150);//eye color
    triangle(265,270,290,270,280,280);//left eye 
    fill(55);
    triangle(291,295,270,320,296,355);//left tusk beginning
    fill(150);
    quad(287,345,276,330,245,360,245,380);// left tusk
    
   
    



    


    //Mouse coordinate finder. Use this code to help place your shapes. 

    fill(0); //mouse coordinate finder
    text("("+mouseX+","+mouseY+")", mouseX, mouseY);
  }
}

In this project you will write a program using [Processing](https://processing.org) that displays any animal of your choosing. You can use almost any drawing functions that you would like, you can find the full list at the [Processing Reference](https://processing.org/reference) (See note below).  Your program will need to be divided into at least two functions `void setup()` and `void draw()`. You may find slides of the [apjavaProcessing slide presentation](https://docs.google.com/presentation/d/1DUtunRnAj5jY_YvGynqyXmAyOOCeLYLn17qAXDr2NfE/edit?usp=sharing) helpful. 

When you are happy with the appearance of your virtual pet, you will post your finished program on a website. You can get a free [GitHub](https://github.com) account for your website. Instructions on how to put your program on a GitHub website are on slides of the [apjavaProcessing slide presentation](https://docs.google.com/presentation/d/1FIV9P78JnVVpMvpW-TOuUO0uFG8pLYE3kHGJubOZXEE/edit?usp=sharing). Submit the link to your website on google classroom.

In the next assignment we will [use an Arduino to interact with your virtual pet](https://github.com/APCSLowell/LightSensorController#use-an-adafruit-circuit-playground-as-an-input-device-in-a-processing-program). As you work on your design, think about an element of the design that could be changed with a single variable.

Note: The following Processing functions do not work on the web:
----------------------------------------------------------
+ `circle()`
+ `square()`
+ `clear()`
+ `delay()`
+ `System.out.println()`
+ `System.out.print()`
+ `push()` and `pop()`
+ Using `CHORD` or `PIE` modes with `arc()`
+ Using an image as an argument in `background()`
+ Arduino code

Sample Virtual Pet Pages: 

[Ms.Padilla](https://mspadilla.github.io/VirtualPet/)
