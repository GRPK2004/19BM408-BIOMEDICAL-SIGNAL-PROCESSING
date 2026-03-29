# GENERATION OF STANDARD DISCRETE-TIME SIGNALS
# AIM:
To generate and plot standard discrete-time signals using MATLAB.
# APPARATUS REQUIRED:
•	Computer / Laptop
•	MATLAB software
# THEORY:
Discrete-time signals are signals defined only at integer values of time (n).
These signals are basic building blocks in Digital Signal Processing (DSP) and are used for system analysis, filtering, and signal modeling.
Standard discrete-time signals include:
	Unit Impulse
	Unit Step
	Ramp
	Exponential
	Sinusoidal
	Damped Sinusoidal
In MATLAB, discrete-time signals are represented using vectors and plotted using the stem() command.
 Standard Discrete-Time Signals
 
🔹 1. Unit Impulse Signal
δ(n)={■(1,&n=0@0,&n≠0)┤

🔹 2. Unit Step Signal
u(n)={■(1,&n≥0@0,&n<0)┤

🔹 3. Ramp Signal
r(n)=n⋅u(n)

🔹 4. Exponential Signal
x(n)=a^n

🔹 5. Sinusoidal Signal
x(n)=sin⁡(ωn)

🔹 6. Damped Sinusoidal Signal
x(n)=a^n sin⁡(ωn)

# ALGORITHM:
1.	Start the program
2.	Define the sample index n
3.	Generate each standard discrete-time signal
4.	Plot the signal using stem()
5.	Label the axes and title
6.	Stop the program

# MATLAB CODE:
<img width="802" height="1599" alt="image" src="https://github.com/user-attachments/assets/7d9bf2f4-61cf-4264-9085-640c10b7c43c" />
<img width="1080" height="1266" alt="image" src="https://github.com/user-attachments/assets/1f757772-5712-4339-99c7-16f79df4c09c" />


# OUTPUT GRAPH:
<img width="821" height="1452" alt="image" src="https://github.com/user-attachments/assets/3faaa3d7-fd19-4032-b9e4-cbb8fcc00523" />
<img width="919" height="1600" alt="image" src="https://github.com/user-attachments/assets/3a42ca71-5ebb-4bf1-8198-735b6c0dc8af" />

# Result :
Thus, standard discrete-time signals were successfully generated and plotted using MATLAB.



