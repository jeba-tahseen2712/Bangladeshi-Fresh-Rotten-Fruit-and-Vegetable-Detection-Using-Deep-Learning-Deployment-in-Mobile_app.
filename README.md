# Bangladeshi Fresh-Rotten Fruit and Vegetable Detection Using Deep Learning Deployment in Effective Application.
<p>
This project addresses fruit and vegetable spoilage in Bangladesh using deep learning and computer vision. A device powered by a CNN algorithm was developed to classify fresh and rotten produce, outperforming KNN and SVM models. An Android app was also created for easy access, allowing users to take a photo and get instant results. This innovation aims to reduce waste and benefit farmers, businesses, and the public.
</p>

## Used Libraries:
-opencv-python<br>
-numpy<br>
-tqdm<br>
-python-csv<br>
-sklearn<br>
-tensorflow==2.3.0<br>
-pyppeteer<br>
-keras<br>
-mlxtend<br>
-datetime<br>
**Remove Image Background**<br>
-opencv-python<br>
-tqdm<br>
-python-csv<br>
-pandas<br>
-rembg<br>

## Data Collection
<p>We used some commonly available Bangladeshi fruits and vegetables in our research. We have collected our required dataset from Google.com and kaggle.com. we collected two categories’ data fruits and vegetables. For classification, the dataset includes fresh fruits, rotten fruits, and fresh vegetables, rotten vegetables. The fruits data set is divided into 6 types and vegetables is divided into 5 types.</p>

![image](https://github.com/user-attachments/assets/349dd59a-807b-43bb-94b3-5afa0097d80f)

## Data preprocessing:
![image](https://github.com/user-attachments/assets/9d2b0f0d-ecd5-404e-9278-0f9f7ad5dfb7)

## System Architecture:
<p> Bangladesh, with its agriculture-driven economy contributing 14.2% to GDP and employing 42.7% of the workforce, heavily relies on fruits and vegetables. These are vital for health, offering essential nutrients and preventing diseases like cancer and cardiovascular conditions. However, spoilage causes significant losses for farmers and retailers due to poor financial conditions and inadequate preservation methods. Differentiating fresh produce from decayed items is crucial to minimize waste and enhance safety. Automation technology offers a solution by enabling early detection of spoiled fruits and vegetables, reducing losses in the agricultural sector. In global trade, the long transportation process and climate challenges like temperature rise and instability further impact the quality and export of produce. Monitoring freshness and vitality during export/import is essential to improve storage and maintain quality standards, ensuring sustainability in the industry.
</p>

![image](https://github.com/user-attachments/assets/47c4f4c4-68fb-4408-99dd-19600509f87e)



## Algorithm Accuracy Comparison

| Algorithm | Accuracy |
|-----------|----------|
| CNN       | 95%      |
| SVM       | 66%      |
| KNN       | 64%      |


## Experimental Result

**Model accuracy:** 
<p>Model accuracy is a statistic used to assess that what model is most effective in detecting patterns and correlations among data samples depending on the information, or trained, information. In every phase of the process, we see that the overall accuracy keeps rising. Then, we reach an accuracy of up to 95 percent, which is training accuracy, as well as an appropriate Val accuracy of 78 percent.</p>

![image](https://github.com/user-attachments/assets/8abe7673-d69e-4add-809b-c4fa2eb38cf5)

**Model Loss:**
<P>
  In other words, loss is a measure of how poorly the model predicted a particular case. This loss-v-loss (validation loss) method graph demonstrates that the loss is falling. This equates to 7%. The validation loss can be calculated on the v-set once our data has been processed (validation set).
</P>

![image](https://github.com/user-attachments/assets/4913f0c1-5234-4df0-a226-3ceb1ded1ae5)
![image](https://github.com/user-attachments/assets/a6a472c9-5c44-4479-9be1-5331d112ba69)

## **OutPut**
<p>Here are some output examples. our system can easily detect rotten fruits and vegetables. We can see here when we selected fresh jackfruit then our system detects it and provide 99.28% accuracy beside when we select a rotten jackfruit then our system checked how many percent rotten and it was 87.27% rotten. In this same way is followed by other fruit and vegetable.</p>


Fresh Fruits:
![image](https://github.com/user-attachments/assets/e16912af-d29e-4d49-ad66-b9680e740041)
![image](https://github.com/user-attachments/assets/65e606c4-f317-4083-b961-fdfa3ff6e070)




