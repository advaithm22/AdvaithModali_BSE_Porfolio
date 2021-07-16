# Image Recognition Using Raspberry Pi 
In this project, I use Raspberry Pi and TensorFlow to train the computer to interpret images of common objects and classify them. After analyzing the image, the Raspberry Pi will output the subject of the image to the user, providing a range of possible outputs and the chance of the image being each of the listed possibilities. My specific goal is to use the program to analyze models of chemical compounds and output the name of the compound to the user.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Advaith Modali | Archbishop Mitty High School | Computer Science/Electrical Engineering | Incoming Senior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2020/05/facial-recognition-data-points-6.jpg)
![Relevant Name](https://www.raspberrypi.org/homepage-9df4b/static/532b4c25752c4235d76cc41051baf9ab/16e7d/877fb653-7b43-4931-9cee-977a22571f65_3b%2BAngle%2B2%2Brefresh.jpg)
  
# First Milestone
My first milestone was setting up the Raspberry Pi with the appropriate operating system and monitor, as well as writing the code in the terminal to complete basic image recognition of simple images. Using TensorFlow and Python, I was able to download all the necessary modules which contain files that carry out the process of image recognition. Following this, I trained the Pi with a simple image of a panda and it was able to produce a list of potential outputs of the animal which could be in the image, with the panda receiving the highest probability. However, the Raspberry Pi ran out of storage, so I continued the project on a Macbook. Towards the end of the project, I will transfer the model to the Pi, which will perform the classification. 

[![Advaith's First Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1626108347/video_to_markdown/images/youtube--DQkVnk6YrMI-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=DQkVnk6YrMI "Advaith's First Milestone") {:target="_blank" rel="noopener"}

# Second Milestone
My second milestone was to use a dataset and import it into the terminal of my computer to start using it to train a model capable. At first I chose a dataset with over 4.4 million files of known chemical compounds, with the goal of using a trained model to interpret the image and output the name of the compound to the user. However, due to the size of the dataset, I was unable to use the trained model to classify the images. To fix this issue, I used an already existing dataset (https://people.csail.mit.edu/lavanya/fmd.html). This dataset consists of images of everyday objects, such as leather, glass, and fabric, with each general class having about 100 images. In the next milestone, my goal is to use the new dataset and train a model capable of image recognition. Ultimately, the final product will be transferred to the Raspberry Pi using a feature in TensorFlow.

Here is the code that I used from the github:
<img src="images/Screen Shot 2021-07-16 at 9.52.34 AM.png" width=250 align=right style="float:right; padding-right:10px">

[![Advaith's Second Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574014/video_to_markdown/images/youtube--y3VAmNlER5Y-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=y3VAmNlER5Y&feature=emb_logo "Second Milestone"){:target="_blank" rel="noopener"}
# Final Milestone
  

My first milestone was setting up and hooking up the Raspberry Pi and all the necessary components onto my tv. The heatsinks, the sd card, and the controller were all added to ensure that the Raspberry Pi was working. Instead of the Raspberry Pi Os software, I had to first download a different software called Retro Pie. With Retro Pie, I needed to download an Imager for Raspberry Pi. Raspberry Pi Imager automatically downloads a list of the latest versions of Raspbian supported by the Raspberry Pi. Raspbian is the typical Raspberry Pi Os software, the one I needed on the Raspberry Pi was Retro Pi. With the included SD card, I plugged in the SD into my computer and launched the Imager. The imager allowed me to set the Operating System to Retro Pi instead of Raspbian onto the SD card. With the OS imaged onto the SD, I plugged the SD card back into the Raspberry Pi and rebooted the system and Retro Bi booted up.

[![Advaith's Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612574117/video_to_markdown/images/youtube--CaCazFBhYKs-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=CaCazFBhYKs "First Milestone"){:target="_blank" rel="noopener"}
