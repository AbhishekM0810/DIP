# Develop the program to perform linear transformation on a image


from PIL import Image
 
img = Image.open("cybersecurity.jpg") 
 
rotate_img= img.rotate(45)
 
rotate_img.show() 


![image](https://user-images.githubusercontent.com/97161303/148198574-23f2d867-daa8-486f-909d-92a2d613d756.png)
