# Face_Recognition_System

System Requirements:
   1)Ubuntu 19.04
   2)NVIDIA Geforce GTX 1080
   3)Ip camera
   
  
Libraries required:
   1)Opencv
   2)Numpy==1.16.0
   3)sqlite3
   4)Tensorflow
   5)Keras
   6)Torch
   5)Numba
   
 Installation of CUDA:
      1)Nvidia Driver version -418.67
      2)Cuda version : 10.1
      3)Installation:https://towardsdatascience.com/tensorflow-gpu-installation-made-easy-use-conda-instead-of-pip-52e5249374bc
      
 Face Detection: MTCNN
 Facial Features Extraction: Inception Resnet Model-generates 128 facial embeddings
      
     
 Procedure:
   Training:
      1)Open the terminal and activate the environment by entering the command conda activate tf-gpu
      2)For training the program with a face, open Master_Data_Collection
      3)Open training_input.py in your code editor and change the Ip address.
      4)Check whether you can access GPU via Cuda by enterring the command nvidia-smi in your terminal.
      5)Now Run the training_input.py with your python intrepretor.
      6)You need to enter the ID of the person by which it identifies a face uniquely.
      7)If your Camera Connection is good then you can see the live feed from camera from your system.
      8)Keep the camera at correct angle so that your face gets detected 
      9)Now turn your face slowly to right and left directions so that left,right and centre parts are took for facial feature          extraction.
      10)After you're done press 'q' to stop it.
      11)You can check the 128 facial embeddings of left,right,centre of the in facerec1_128D.txt file.
      
   Recognition:
        1)Open the terminal and activate the environment by entering the command conda activate tf-gpu
        2)For Recognizing a face open Recognition Folder.
        3)Open start_recognizing.py in your code editor and change the Ip address and change the location of facerec1_128D.txt
          to location where you saved your recently updated facerec1_128D.txt from training phase or just you can simply replace
          older one by new.
        4)Now create a database in Recognition folder using SqliteStudio
        5)
 
      
      
      
 
      
   
