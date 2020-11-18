# Projects Accomplished
--------------------------
This repository contains information pertaining to the list of projects accomplished. These projects are basically research projects carried out by me and my team of students and faculties covering the domains like Deep Learning, Internet Of Things, Information Security, Image Processing.


# List Of Projects 
1. [Electricity theft detection](https://github.com/jason1987martis/Major-Projects/blob/main/README.md#electricity-theft-detection)
2. [Reckoning of Emotions using Posture Features](https://github.com/jason1987martis/Major-Projects/blob/main/README.md#Assessment-of-Image-Enhancement-Techniques-for-Photo-Sketch-Matching)
3. [A Rapid Automated Process for Organizing Bacterial Cluster Segments Using Deep Neural Networks](https://github.com/jason1987martis/Major-Projects/blob/main/README.md#A-Rapid-Automated-Process-for-Organizing-Bacterial-Cluster-Segments-Using-Deep-Neural-Networks)
4. [A Novel Key Generation Approach Based on Facial Image Features for Stream Cipher System](https://github.com/jason1987martis/Major-Projects/blob/main/README.md#A-Novel-Key-Generation-Approach-Based-on-Facial-Image-Features-for-Stream-Cipher-System)

Electricity theft detection
-------------------------------------
**Features of the application** - For the past few years we have been facing a great electricity crisis since the demand of electricity is more than the production. Hence it is very important to manage electricity efficiently. In this regard one of the major challenges in electricity management is misuse of the power consumption due to electricity theft in public area. In this paper we propose a technique that detects the electricity theft by remotely monitoring the electricity meter readings to see whether it is within the specified threshold value and thus minimizing the misuse of electric power consumption in public areas. It also aims in the reduction of manual workload by tracking the data automatically. The paper mainly focuses on the implementation of the concept using Internet of Things (IoT) as the underlying framework to achieve real time monitoring through Raspberry pi board.

**Technologies Used**
1. Python
2. IoT
3. MQTT

**Conclusion and Future Scope** - Our system can be used to monitor power consumption in  public  places  using  an  IoT  board  (raspberry  pi)  as  the underlying  framework  which  acts  as  an  interface  between  the energy meter and the remotely placed system.  Collection of data from the energy meter in the form of pulses and sent to GPIO pin of raspberry pi which is processed continuously by the system and the  processed  data  is  stored  in  the  database  for  the  later inspections. Calculation of threshold value based on test cases and if the meter reading value exceeds the threshold value it shows variation in graph and also sends notification to the concerned authority. This system also reduces lot of work load of power station officials. As  a  future  work,  following  features  can  be incorporated to the implemented system: 1. wireless connection could be established between the energy meter and Raspberry Pi. 2. A remote monitoring of the switch could be implemented so that  the  required  appliances  could  be  controlled  at  the  station when there is a threat of theft. 3. The system could be made still better by generating an automated electricity bill. 4. This system can also be made to promote a prepaid electricity system based on  the  continuous  power  monitoring.  5.  The  system  could  be made to work offline through some better implications.  

**Paper Link** - https://ieeexplore.ieee.org/abstract/document/8455088/

Reckoning of Emotions using Posture Features
-------------------------------------
**Features of the application** - Emotions are noteworthy signs to understand the intentions of others peoples during communication with them. Similarly, in order to identify the different emotional states of individual such as joy, sadness, and anger, using facial expressions and vocal tone are less effective due to the variations in facial and vocal outputs. Thus, for recognizing emotions intensely without variation physique postures analysis can give effective outputs. Thus, physique posture analysis of the individual can be obtained by mapping the joints using Reeb graph which plots all the joints into carvative structure to learn posture, and the angles between the joints of posture are detected by law of cosines which depicts the vigorous expression along with postures. In addition to that much more reliable recognition of emotions without distractions can be obtained through the detailed features by preprocessing the input image through the fusion of Median and Wiener filter which avoids all the five types of noise occurrence so detailed features such as Invariant, Depth sequential silhouettes and Spatiotemporal body joint can be obtained to aid efficient analysis of posture that can pave a way to identify the different emotions by tactic Tree based classifier to get better performance in terms of execution time and accuracy. 

**Technologies Used**
1. Machine Learning
2. Image Processing
3. C#

**Conclusion and Future Scope** - Thus, the emotions of the people are identified by the physique posture recognition through joint detection and angle of posture by Reeb graph methodology and the law of cosines with aid of tactic preprocessing and feature extraction techniques. These strategies lift up the accuracy of the emotion recognition by postures to about 97%. The future extension of this work can be focused to improve accuracy drops during recognition of certain emotions which is of very less values around 75% due to the fact neutral factor.

**Paper Link** - https://www.tandfonline.com/doi/abs/10.1080/19361610.2019.1645530?journalCode=wasr20

A Rapid Automated Process for Organizing Bacterial Cluster Segments Using Deep Neural Networks
-------------------------------------
**Features of the application** - The acknowledgement of the bacterial species is essential since the organic information on microorganisms is critical in medication, veterinary science, organic chemistry, nourishment industry or cultivation. A large portion of the organisms have a positive effect on everyday issues; they can be an explanation of numerous illnesses. Along these lines, automating the procedure of acknowledgement can discover application in restorative counteractive action and treatment sciences. One of the most significant highlights that can be perceived in the pictures is the state of a microscopic organisms cell. In this research article, the indispensable shapes like round and hollow, circular and winding are categorized using deep learning approach. Nevertheless, the procedure of perceiving microbes is dependent on the shape would be a troublesome one because numerous bacteria share primarily the same forms. Secondly, the most separating highlight is the shape and the size of the microscopic organisms. Overall if it was not an automated approach, then it is difficult to classify the bacterial colonies. Experimental outcomes of the proposed methodology are carried out using three different models, namely VGG. Mobile Net and Inception out of which VGG has shown remarkable progress of 99%.

**Technologies Used**
1. CNN
2. Image Processing and Conversion
3. Transfer Learning

**Conclusion and Future Scope** - Bacteria and their species have been in this earth for millions of years. They will also continue living for another million years to come. Humans have found the applications of bacteria very recently and learned to classify them. Unfortunately, the classification methodologies are too primitive and consume too much time and effort. We have proposed an innovative effort to classify species of bacteria using deep learning and compared our results with three standard models of deep learning. It was found out that SVGG proved to be the best model for genera classification. We can further improvise our work by developing a feedback system which can further allow identifying newer species of bacteria by using reinforcement learning. Our idea also can be further used to identify viruses and other single-celled organisms.

**Paper Link** - https://ieeexplore.ieee.org/abstract/document/9214173

A Novel Key Generation Approach Based on Facial Image Features for Stream Cipher System
-------------------------------------
**Features of the application** - Security preservation is considered as one of the major concerns of our day to day routine in this digital world for any online transactions. Time to time, we have been witnessing an enormous amount of security threats and stealing of various kind of digital information over the online network. In this regard, lots of cryptographic algorithms based on secret key generation techniques have been implemented to boost up the security aspect of network systems that preserve the confidentiality of digital information. Despite this, intelligent intruders are still able to crack the key generation technique, thus stealing the data. In this research article, we propose an innovative approach for generating a pseudo-pseudo-random key sequence that serves as a base for the encryption/decryption process. We carry out the key generation process by extracting the essential features from a facial image and based on the extracted features; we generate a pseudo-random key sequence that acts as a primary entity for the efficient encryption/decryption process. Experimental findings related to the pseudo-random key is validated through chi-Square, Runs Up-down and period of subsequences test. Outcomes of these have subsequently passed in achieving an ideal key.

**Technologies Used**
1. Java 
2. HTML and CSS
3. JavaScript
4. MATLAB

**Conclusion and Future Scope** - In this research article, we have successfully implemented the process of encryption and decryption using the pseudo-random key generation technique. We were successful in achieving a novel procedure for pseudo-random key generation using the features extracted from the facial image through SURF algorithm. Experimental results of the Chi- Square test and Runs Up-down test confirms the strength of the key generated through LFSR in terms of the randomness factor. Graphical representation in Fig. 9 proves that the generated pseudo-random key has a higher value of non- repeating subsequence in most of the cases, which are several times larger than the fetched seed value into LFSR. From this, it is proved to generate a very long pseudo- random key sequence. In future, the work can be enhanced to increase the strength of the random key by considering only selected facial features to achieve more randomness. The current research that applied a single feature extraction technique can be extended by using multiple feature extractors which possibly strengthens the length and randomness of the generated key. The proposed system can also be carried forward to encrypt various other types of information, including stenographic applications.

**Paper Link** - https://ieeexplore.ieee.org/abstract/document/9214095


