# Custom Face Detction
 This project is for detecting face from Image, video also using web-cam with TensorFlow Object Detection API.
 
 ## Steps
 1. Please install this anaconda3 exe file. By clicking next next only.
    https://repo.continuum.io/archive/Anaconda3-5.2.0-Windows-x86_64.exe
 2. After Installing it please search conda file location under the Scripts Folder. Then copy the file location.
 3. Search for Environment variable in your pc. From system properties go to the Environment variable.
 4. Then double click on the bellow box path. like this-
 
    <img src="https://github.com/ummerubaiyat/face_detction/blob/master/doc/2.PNG">
    
 5. Now click new, then pest your coppied conda path. Then press OK.
 6. After your conda path is set up. Next search anaconda prompt on your pc & run it as an administrator.
 7. Please write this command bellow
 
    `conda create -n tensorflow pip python=3.6`
 8. Type y and press Enter
   
    <img src="https://github.com/ummerubaiyat/face_detction/blob/master/doc/3.PNG">
    
 9. now write
 
    ```
    activate tensorflow
    pip install tensorflow
    pip install pillow
    pip install matplotlib
    pip install lxml
    pip install jupyter notebook
    pip install opencv-python
    
    ```
10. Now clone this repository
11. Open the folder & go to the object_detection folder . Then copy the path.
12. Write cd and paste the location. My one is look like this ->
   
    `cd J:\prapti\tensorflow3\models\research\object_detection'
13. Now write
    
    `idle`

#### This will open a python shell
14. Now click on File & open object_detection_image.py
15. Finally click run then click run module

After a minute it will open an detecteted image.

<img src="https://github.com/ummerubaiyat/face_detction/blob/master/doc/4.PNG">
