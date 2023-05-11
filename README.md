# Video_super-resolution_ESRGAN

This project aims to implement the ESRGAN (Enhanced Super-Resolution Generative Adversarial Networks) algorithm for video super-resolution. 
ESRGAN is a state-of-the-art deep learning model that is capable of producing high-quality super-resolved images with natural textures and details.

following are the steps to run our model

1. Open the Notebook "Video_super_resolution.ipynb" link and run the code in Google Colabs.
  
2. Run the first cell to clone the required directories and libraries. Once you run this code you should see a directory named Real-ESRGAN.
 
3. Run the second cell to create some essential folders,Once you RUN this cell you should see a folder named "input_videos" inside the Real-ESRGAN directory.

4. Upload the video you want to enhance in this folder(you can upload multiple videos at the same time).

5. initilize the variable named "fps" according to the fps of input video. Set the tile size in the inference line  according to your needs (lower tile size may give better result but also take more time ).

5. Run the next block of code , after running this code should you should see the enhanced videos in "output_videos" folder under Real-ESRGAN model(note that the output video might not be in same order as input videos), you can directly download the enhanced videos to your local device.

6. You can execute the final block of code to clear all files from colab notebook.       
 


