# Wafer-project
To know about the project, read the Problem Statement.docx and the Program architecture.ppt
To run the project, follow the below steps.
Download all the files.
Install PyCharm.
Open the "main.py" file.
In the terminal type -> pip install -r requirements.txt
After installing all the necessary libraries.
Run the main.py file.
Open the localhost in the web browser.
You can see the Web API to predict the wafer quality.
Place the Folder path of which csv files need to be predicted in the text box. Here it is "Prediction_Raw_Files_Validated".
Click the Custom File Predict and you can see the output. You will also get the output csv file in "Prediction_Output_File" folder.
In case you want to train the model again.
Install Postman.
Pass the URL:localhost:5000/train and along with that send the file's folder path which you want to train as json format. Here it is 'folderPath':'Training_Batch_Files'.
After getting output "Training Successful", do the prediction as mentioned above.
