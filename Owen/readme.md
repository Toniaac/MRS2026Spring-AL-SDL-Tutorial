<h1>Resource-Efficient Bayesian Optimization for Self-Calibrating Liquid Handling</h1>

<h2>Speaker:</h2>
<b>Owen Alfred Melville, PhD</b>
<br>Staff Scientist, Polymer SDL
<br>University of Toronto
<br>Acceleration Consortium

<h2>Description</h2>
In this presentation, I will go over why using Bayesian Optimization for liquids can be a helpful tool in your arsenal for your self-driving lab. I will present a live demo of the calibration workflow on the North Robot system. I will discuss how you can create a tool for liquid calibration yourself, using a Bayesian framework in Python such as Ax. 

<h2>Results: </h2>

The optimizer, seeded with our manual data, converged on a very good solution by cycle 12 (optimization cycle 8), with average volume = 50.8 mL (target was 50.0) with a CV of 0.05 and a time of 25s per run. Not bad for something that started at 15 uL! The best parameters were:
- Overaspirate 10.3uL extra
- Aspirate at speed 12
- Wait 3.5 seconds after aspiration
- Use 0.435mL blowout volume
- Dispense at speed 2
- No dispense wait time

<img width="955" height="554" alt="MRS _ Screenshot" src="https://github.com/user-attachments/assets/5706641a-0c5f-4204-bbab-5a7cfd8300a2" />

<img width="3567" height="2368" alt="image" src="https://github.com/user-attachments/assets/8d03379d-e431-4c74-8972-d8c5156cba8e" />



<h2>Links:</h2>
<br>Link to North Robot Github: https://github.com/AccelerationConsortium/North-Cytation
<br>Link to Calibration Folder: https://github.com/AccelerationConsortium/North-Cytation/tree/main/calibration_modular_v2
<br>Link to GUI for Demo: https://github.com/AccelerationConsortium/North-Cytation/blob/main/calibration_modular_v2/calibration_test_gui.py
<br>Link to live stream of robot: https://www.youtube.com/playlist?list=PL8uZlc2CEpekQJl7h8FpY08JgcZwzdUVj

<h2>Other Contributors:</h2>
Dr. Nipun Gupta (Acceleration Consortium)
<br>Dr. Chanelle Brown (Acceleration Consortium)
<br>Dr. Harrison Mills (Acceleration Consortium)
<br>Dr. Sanjay Patel (Acceleration Consortium)
<br>Dr. Zeqing Bao (Acceleration Consortium)
<br>Dr. Ilya Yakavets (Acceleration Consortium)
<br>Dr. Yimu Zhao (Acceleration Consortium)
<br>Dr. Wei Yang Tham (Acceleration Consortium)
<br>Edison Lin (Acceleration Consortium)
<br>Monique Ngan (McGill University)

