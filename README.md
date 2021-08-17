# Pulse dataset

| Number of Instances | Area | Attrubute Characteristics | Number of attributes | Associated Tasks | Missing Values? |
|:-------------------:|:----:|:-------------------------:|:--------------------:|:----------------:|:---------------:|
|  300                |Health| Real                      | 4                    | Regression       | No              |


### Data Set Information:

The dataset contains 300 heart rate measurements made with four different methods simultaneously. Heart rate measurements were made using the following methods:  
- palpation (the pulse at the carotid artery),
- OHR (using sports watch),
- video-based from the face (using a laptop and built camera),
- heart rate sensor on chest strap.  

The chest strap measurement serves as a reference measurement. It is considered the most accurate way to measure heart rate because it uses the ECG method.  
All measurements were performed on one person at different time intervals and under varying conditions (lighting, time of day). Since the measurements were performed on one person only, attempts were made to carry out the measurements in various circumstances, taking into account factors affecting the heart rate, such as stress, emotions, hydration, sugar levels, caffeine levels, exercise, sleep.  
Each measurement took one minute because that is how much the palpation method requires to minimize errors. For the other methods of measuring pulse, the result obtained is the average of the measurements per minute.
Timing-related reflexes and finger pulse sensing when palpating could affect the simultaneous measurement results of heart rate using four different methods at once.  
The dataset can be used to perform regression tasks and predictive modeling processes. 


### The columns in this dataset are:
- palpation: the pulse at the carotid artery,
- OHR: heart rate measured using sports watch (Polar Ignite),
- face image: heart rate measurement using face detected from camera image  and algorithm,
- ECG: chest strap measurement (Polar H10).
