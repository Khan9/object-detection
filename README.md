# object-detection

################################## Testing ###################################


	- Download yolo_weights.h5 file from this link : https://drive.google.com/drive/folders/1UizsR9IZCjUOiXLh-XZAyKgaWcXdd-oU?usp=sharing 
		and keep that file in model_data directory

	
	- To run other video, copy the video in the same directory where yolo_video.py located 
	  and change video_path field with that video name in yolo.py file on line 173.

 	- run yolo_video.py

press Q to quit

 P.S: 	- If you want to run the classifier using custom trained dataset (6 classes trained with 674 samples) , then download the custom_dataset_weights.h5 file from this link
		https://drive.google.com/drive/folders/1UizsR9IZCjUOiXLh-XZAyKgaWcXdd-oU?usp=sharing 
	 keep that file in model_data directory 	
	 AND uncomment the line 21 and comment line 20 of yolo.py file 



################################# Testing using custom dataset ###################################



	- To test with custom-trained dataset ( 6 classes, 674 samples ), 
		comment 20th line and uncomment 21 line of yolo.py file

Due to the inconsistent broadband speed of ISP, I was unable to train the model with google colab. 
I trained the model with only 5 epochs. So the loss value was very high and model didn't perform well.
 But I think it will work better if more data, as well as classes, are added and iterate the train with 70 epochs.
 the file size is too big to upload on github.  I have kept that file in my local repo. 
 
