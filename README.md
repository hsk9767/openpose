# Abnormal-Situation-Detection-in-Cap


## 1. Purpose



  Although violent situations in cap are taking place quite often, there is no system which notifies the emergencies automatically. So, we embodied the idea using only image data taking advantages of ***Openpose(Zhe et al.), Deepsort(Nicholas et al.).***
 
 ## 2. How to implement 
 
 

Download Model : [Google Drive](https://drive.google.com/drive/folders/16IkXWthjqXp0S5wZeGFwT2IhTFuqSgyU?usp=sharing)
  
    Download two files in shared google drive to **./default_checkpoints**

Run Demo

    run demo.py --video path/to/video(image) --checkpoint-path default_checkpoints/checkpoint_iter_147000.pth 
    You can use --video cam device number and set --save-path to save output images.
    
    
