# Phase_Amplitude_Coupling.PAC
Measuring Phase-Amplitude Coupling (PAC)

## Phase-Locking-Value as Used in Mormann et al. (2005)

$$
\Huge PLV = \left|\frac{\sum e^{i( \phi_{l}  -\phi_{a_{u}}  )}}{n}\right|
$$

$$\large n= \small \text{the total number of data points} $$

$$\large \phi_{l}  =\small \text{the phase angle of the lower frequency band at data point t} $$

$$\large \phi_{a_{u}} =\small \text{the phase angle of the Hilbert transformed upper frequency band amplitude time series} $$


<img src="https://github.com/DrAliSeif/Phase_Amplitude_Coupling.PAC/blob/main/PVL(Mormann)/PVL_Mormann_example.png" width=100% height=100%>




## Mean Vector Length by Özkurt and Schnitzler (2011)

$$
\large MVL_{Özkurt} = \frac{1}{\sqrt{N}} \left|\frac{ \frac{1}{N} \sum a_{u} e^{i\phi_{l}} }{\quad \frac{1}{N} \sum a_{u}^2}\right| 
$$

$$\large n= \small \text{the total number of data points} $$

$$\large \phi_{l}  =\small \text{the phase angle of the lower frequency band at data point t} $$

$$\large a_{u} =\small \text{the phase angle of the upper frequency band amplitude time series} $$


<img src="https://github.com/DrAliSeif/Phase_Amplitude_Coupling.PAC/blob/main/MVL(%C3%96zkurt)/cropped_example2.png" width=100% height=100%>

## Mean Vector Length by Canolty et al. (2006)

$$
\Huge MVL_{Canolty} = \left|\frac{\sum a_{u} e^{i(\phi_{l})}}{n}\right|
$$

$$\large n= \small \text{the total number of data points} $$

$$\large \phi_{l}  =\small \text{the phase angle of the lower frequency band at data point t} $$

$$\large a_{u} =\small \text{the phase angle of the upper frequency band amplitude time series} $$



<img src="https://github.com/DrAliSeif/Phase_Amplitude_Coupling.PAC/blob/main/MVL(Canolty)/MVL_Canolty_example2.png" width=100% height=100%>
