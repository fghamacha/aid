# 1. Introduction :

By following those steps, you will be able to display a message for happy Aïd in linux environment

![alt text](https://github.com/fghamacha/aid/blob/master/Aid-mubarak.gif?raw=true)

# 2. Steps :

1. Create an image containing your message

You can use paint  for exemple to create your jpeg file or use my file Aid-mubarak-Maj.jpg 

2. convert you image into ASCII art 

Use the following web site to convert you image into ASCII art  ==> https://www.text-image.com/convert/ascii.html 

3.download the aid-mubarak.sh 

download aid-mubarak.sh file and edit it with your favorite text editor ( vim, nano ..)

4.  Insert the ASCII art 

Copy the ASCSII art to the file aid-mubarak.sh in the line juste next  cat << "EOF" 

5. save your file 


esc then wq! with vim 

6. give x rights to your file 
chmod aid-mubarak.sh

7. zoom out your command window if your ASCII art is to big 

8. run your script 
./aid-mubarak.sh
