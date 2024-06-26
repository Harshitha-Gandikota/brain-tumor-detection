# brain-tumor-detection
## to run the code follow the below steps
1. Open the file Google collab.
2. Change the runtime type to *T4 GPU*
3. Run the 1st 4 cells expect the commented one.
4. Before running the preparing the custom dataset. 
     i. go to roboflow.com and sign in.
     ii. go to universe and select the brain tumor dataset.
     iii. click on download dataset. select the version- YOLOv8. Export it.
     iv. copy the displayed code.
5. Paste it and run the cell.
6. Run the cell in custom training. You change the epoch value as required.
7. Run the cell in Validate Custom Model.
8. Lastly run the cell in Inference with custom model. In the place of source, you can give the image or video path you want to detect.
<br>
<br>
Epoch - An epoch in YOLO refers to one complete cycle of training the model on the entire dataset. During one epoch, the model sees and learns from each training example once. It's like reading a book from start to finish one time to understand the content.
<br>
Roboflow - Roboflow makes it simple to label and annotate images, which is essential for training models like YOLO. It helps increase your dataset by creating variations of your images, improving model performance. Roboflow can convert your data into the format needed for different models, saving you time. It keeps your datasets organized and easily accessible. Roboflow integrates well with popular machine learning frameworks, making it easier to train your models.

