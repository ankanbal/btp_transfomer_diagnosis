# Smart Transformer Diagnosis System

The smart diagnosis system is a project directed towards more safer, better and smarter use of distribution level transformers.
The objective of the project is to make a smart device that can sit on top pf a transformer that can sense and send live data to a concerned server where the data can be used to predict when the transformer in question is likely to fail..


## Tasks done
1. Read about the working of a Transformers and the likely features that can lead to failures.
2. Read two previous works that were directed towards a smard grid system and a transformer detection system.
3. Basic circuit design is complete.
4. Succesfuuly taken data from the arduino.
5. The data is planned to use on an ML algorithm for prediction.

## Problems facing
1. About using Raspberry pi3 or NodeMCU for showing data (planned:- for now using NodeMCU)
2. Creating a UI (web as well as a non-web) that can show the results. (planned:- learning Java Swing/pyhton Tkinter for that)
3. Whether to use a GPS module to track the respective transformer. (planned:- since transfrmers are stationary, will keep locations of all transformers without using GPS module)
4. How to calculate current. (planned:- using an ACS712 current sensor module)
5. Shortage of Analog pins on NodeMCU (planned:- to use NodeMCU as a Wifi module and Arduino as the MCU)
