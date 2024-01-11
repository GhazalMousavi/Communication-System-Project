# Communication-System-Project
Rayleigh distribution, Random Process and Quantization in Communication Systems
 In this project, we have three parts. 

1. Rayleigh Distribution : In the first part, we will review the Rayleigh distribution.

2. Random Processes : In the second part, we will analyze a random process to see if it is a Stationary Stochastic Process (WSS). If it's not, we will explore ways to make it a WSS process.

3. Quantization : In the third part, we will focus on pulse modulation and work on building a digital transmitter and receiver that can handle noise and decoding.

1-1: Plotting the probability density function (PDF) of the Rayleigh distribution
 
![image](image/Rayleigh_plot.png)

1-2: Plotting the PDF of two random variables with a Normal distribution having a mean of zero and a variance of one

![image](image/normal_N1.png)

1-3: Generating and plotting Rayleigh random variable using two normal random variables

![image](image/RayleighN1.png)

 1-4: The Impact of Increasing N

![image](image/normal_N2.png)

![image](image/RayleighN2.png)

 When we increase the value of `N` from 1000 to 100000, the histogram tends to be more accurate because we have a larger number of samples to represent the distribution of the data. With a larger sample size, the histogram bins can capture the underlying distribution more precisely, resulting in a more accurate representation of the data.

2-2: Plotting mean of random process X

 ![image](image/meanX.png)

2-3: Plotting autocorrelation of random process X

 ![image](image/Rx1.png)

2-4 : Plotting mean and autocorrelation of random process X base on theoretical calculations

![image](image/meanX1.png)
![image](image/Rx3.png)

2-5 : 

![image](image/Rx2.png)

3-1 : Definition of continuous signal and sampling and construction of discrete signals 

![image](image/continuous_signal.png)
![image](image/discrete_signals.png)
![image](image/c_d_signals.png)
 
3-3 : Quantization Level Implementation
![image](image/q1.png)
![image](image/q2.png)
 
 3-4 : Digital conversion of quantized signals

![image](image/pulse.png)
![image](image/pulse_code.png)

3-5: Reception of digital signal at the receiver

![image](image/noise.png)

3-6: Decoding of the digital signal at the receiver

![image](image/decode.png)