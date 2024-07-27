A Collection of codes and tutorials on fast Fourier transform and wavelet transform, curated by Chitradeep.
   			                 

# A1. Overview of time domain analysis  

The instructor presents a broad overview of time domain analysis and its wide applications across various domains. Subsequently, the discussion narrows down to two specific tools: the fast Fourier transform and the wavelet transform and how these can be utilized in the context of analyzing long-term solar magnetic activity. A brief mathematical framework behind these tools follows thereafter. The discussion ends by outlining a detailed plan for the rest of the fourth module.

[Link to the lecture slides](https://github.com/deephysics1729/Time_Domain_Analysis/blob/main/Overview.pdf)


# A2. A hands-on session on fast Fourier transform

This submodule aims to perform hands-on time series analysis using numerical fast Fourier transform. We start with the standard procedure of ‘standardizing’ any arbitrary time series. Then we calculate Nyquist's optimum sampling rate for an observed phenomenon of interest in order to capture the desired frequencies in its Fourier spectrum. How a poor sampling rate can introduce ‘aliasing’ in the frequency spectrum and influence the outcome is what we demonstrate next. We also test out the importance of windowing a signal to avoid leakage in the spectrum. We conclude this submodule by evaluating power spectral density of a given Fourier spectrum.

[Link to the Jupyter notebook](https://github.com/deephysics1729/Time_Domain_Analysis/blob/main/Fourier/01_FFT.ipynb)

# A3. A hands-on session on noise characterization 				                      
Time series gleaned from observation of natural phenomena are mostly contaminated by the presence of noise – either colored or uncolored – which in turn poses challenges in determining the ‘true’ frequencies present in the signal. We discuss characterizing the noise in a given time series. We estimate statistical regression parameters and employ them to distill out significant frequencies from the noisy background in the Fourier spectrum.

[Link to the Jupyter notebook](https://github.com/deephysics1729/Time_Domain_Analysis/blob/main/Fourier/02_Noise.ipynb)



# Time domain analysis: Wavelet transform	        			                  


# B1. Overview of discrete and continuous wavelet transform

The instructor outlines the advantages of wavelet transform over a Fourier transform. While the Fourier analysis of an oscillatory signal cannot achieve time-frequency localization and moreover, it often introduces numerical artifacts like overshoot (Gibb’s phenomenon), etc.,  the scalogram constructed from the wavelet coefficients of the same signal can precisely determine the dominant frequencies in the particular time window. In this submodule, we learn about the properties of wavelets, different types of discrete and continuous wavelets, namely Haar wavelet, Daubechies wavelet, and Morlet wavelet, etc., and use them to extract useful information from standardized time series data. 

[Link to the lecture slides](https://github.com/deephysics1729/Time_Domain_Analysis/blob/main/Wavelet/Wavelet.pdf)



# B2. A hands-on session on wavelet transform

In this submodule, approximate and detailed wavelet coefficients are calculated for a given time series at different decomposition levels, followed by reconstruction of the original signal in terms of low- and high-pass components. We also demonstrate the energy flow from one set of dominant frequencies to others at different temporal epochs of the signal. ‘Edge effect’ in the wavelet spectrum is discussed, and the statistical significance of various frequency components is evaluated using the ‘cone-of-influence’ study.

[Link to the MATLAB notebook](https://github.com/deephysics1729/Time_Domain_Analysis/blob/main/Wavelet/wavelet.mlx)

