# Robotic arm report

* I added hand after elbow to make arm more realistic 
```<language>
    glTranslatef(1.0, 0.0, 0.0);
    glRotatef((GLfloat)hand, 0.0, 0.0, 1.0);
    glTranslatef(0.25, 0.0, 0.0);

    glPushMatrix();
    glScalef(0.5, 0.5, 1.0);
    glutWireCube(1.0);
    glPopMatrix();
```
![image](https://github.com/mennatallah-nawar/Robotic-arm/blob/master/Hand.png)

* And I face one problem with fingers motion when I run the attachment code the 
fingers shown as below.

![image](https://github.com/mennatallah-nawar/Robotic-arm/blob/master/old%20position%20(1).png)

which is not make sense unless I change the location of the thumb finger or change 
angles of fingers ,so I change some lines in `void keyboard(unsigned char key, int x, int y)`  

* Here is the final result of robotic arm 
![image](https://github.com/mennatallah-nawar/Robotic-arm/blob/master/1.png)



