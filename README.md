# 2.-Design-and-Simulation-of-uncontrolled-Full-wave-rectifier
## AIM
To design, simulate and analyse Full wave rectifier (Uncontrolled) in MATLAB Simulink.
## APPARATUS REQUIRED
•	MATLAB
## PROCEDURE
1.	Open MATLAB and click on the icon for SIMULINK as shown below
 <img width="522" height="376" alt="image" src="https://github.com/user-attachments/assets/19e8a664-c851-4ee1-8719-d76e3c4ce565" />

Another way is to open is through START icon of MATLAB Start ⇒ Simulink ⇒ Library  browser. 

2.	Click on NEW MODEL or go to FILE ⇒ NEW ⇒ MODEL and a new blank model is created as shown below
 <img width="572" height="382" alt="image" src="https://github.com/user-attachments/assets/e5de3a45-cf07-4467-902b-b8a55bb98bef" />

3.	After creating a blank model you need to open the SIMULINK component storeroom/library by going to View ⇒ Library Browser. Select SIMPOWER SYSTEMS then select Power Electronics library and by right clicking on diode and click on add to the model will add the diode in the blank model. Alternatively you can drag the component directly in the model page as shown below
 <img width="940" height="361" alt="image" src="https://github.com/user-attachments/assets/04fd890e-b12e-4ad1-9b89-560b5ea27a18" />

4.	Similarly go to ELECTRICAL SOURCES ⇒ AC Voltage Source and add it to the model. Select Elements and select “SERIES RLC BRANCH” and add it to the model. Simulink do not perform simulation unless and until a measurement block is present in a system. Since we need to measure the input and output voltages and the load current. To add them select Measurement in SIMPOWER SYSTEMS and then add current measurement and voltage measurement blocks to the model. Oscilloscope is not included in SIMPOWER SYSTEMS and is present in the top most block of the left column that is SIMULINK ⇒ Sinks ⇒ Scope. We can join various blocks by clicking on their edges and then drag the wire till the other connection terminal.
5.	Construct the circuit by joining them together in the form as given below
 <img width="872" height="413" alt="image" src="https://github.com/user-attachments/assets/b94a704c-b6f7-4552-a068-10c8078d9281" />

6.	Now double click the voltage block to set the values of voltage and frequency.
 <img width="349" height="325" alt="image" src="https://github.com/user-attachments/assets/557e4638-687e-4ecd-89af-8c8ff088d496" />

7.	Double click on diode and you can set various parameters for DIODE according to the specific data sheet.
8.	Double click on series RLC branch, Select the Branch type as R and set the values for R.
9.	In the Scope menu “>” is shown which can only be connected to the inverse icon “<” in the measurement blocks.
10.	Double click on SCOPE and then click on parameter icon as shown
 <img width="838" height="377" alt="image" src="https://github.com/user-attachments/assets/867647eb-21c0-479d-b4fd-07f922640042" />

11.	Make the number of axes as required.
12.	Before running the simulation, we have to configure the parameters. Go to Simulation ⇒ Configuration parameters as shown
 <img width="542" height="399" alt="image" src="https://github.com/user-attachments/assets/b5779ed1-4df3-466c-a36d-b9b33b5f65cb" />

13.	Select the ode23tb (Stiff/TR-BDF2) or ode15s (Stiff/NDS) or any suitable solver as
shown below 
 <img width="566" height="401" alt="image" src="https://github.com/user-attachments/assets/3ff8e2f1-3d5a-40e8-97f1-d02e69c7a656" />

14.	Start the simulation by either clicking on Start Simulation icon as shown in below or
by going to Simulation ⇒ Start
 <img width="770" height="308" alt="image" src="https://github.com/user-attachments/assets/eb4ac233-cc13-488b-a555-ef4ab2e3c048" />

15.	Double click on scope and observe the graphs.
16.	Right click on each graph and select the axes properties and label each graph.
17.	Save the file. 
18.	Analyze and record your inference.

## Task
Design, Simulate and analyse the below-given circuit using the following values.
Vin = 100 sin wt
Resistance=1 ohm
Draw the simulated output in the graph sheet.
Write your analysis report as Inference (Current waveform, RMS value)
 
<img width="940" height="567" alt="image" src="https://github.com/user-attachments/assets/ef548704-4f5e-47e8-b847-4badd9cfeb07" />

## Simulation
<img width="1321" height="570" alt="image" src="https://github.com/user-attachments/assets/9facf390-ebc6-46ed-906d-e83685aeabb7" />

## Output
<img width="703" height="628" alt="Screenshot 2025-08-30 104553" src="https://github.com/user-attachments/assets/0d3bb097-0b59-4f08-8a03-29168934312b" />

## Result
Thus the Simulation-of-uncontrolled-Full-wave-rectifier in MATLAB Simulink was studied and verified.
