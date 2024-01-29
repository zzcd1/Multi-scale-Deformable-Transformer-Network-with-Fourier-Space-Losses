# MDTNet: Multi-scale Deformable Transformer Network with Fourier Space Losses Toward Fine-scale Spatiotemporal Precipitation Nowcasting
##  1. Problem Statement
* **Solving the Blurry Prediction Problem in Precipitation Nowcasting through Frequency Domain Analysis**
<div align=center>
<img src='https://github.com/zzcd1/Multi-scale-Deformable-Transformer-Network-with-Fourier-Space-Losses/blob/main/visualizations/fig1.jpg' width='375'/>
</div>

<p align="left">As shown in the above figure, the real-world long-term strong rainfall circumstances’ echo images are enriched in details and complicated in patterns, exhibiting informative and intricate high-frequency component distribution in the frequency domain. To introduce analysis of the blurry problem in precipitation nowcasting from the Fourier space, we give an illustrative visualization. (a), (b), (c) show the ground-truth sampled echo image, the predicted coarse and blurry echo image by state-of-the-art ConvLSTM, and our predicted crisp echo image, respectively. (d), (e), (f) are corresponding power spectrums calculated from the 2D discrete Fourier transform (DFT). (g) shows the radially averaged power spectrum (RAPS). Note that some studies have explored analytical models to describe this spectral fluctuations in atmosphere. In (e), it is obviously that only low frequency part in the middle of the blurry image’s spectrum is close to the ground-truth while high frequency part is almost completely lost. In (g), there is severe high frequency component discrepancy between the blurry prediction result and ground-truth.</p>


Code is coming.

![living](visualizations/38.gif)
![living](visualizations/57.gif)
![living](visualizations/772.gif)
![living](visualizations/988.gif)

<a href="http://s11.flagcounter.com/more/Tl3Q"><img src="https://s11.flagcounter.com/map/Tl3Q/size_m/txt_000000/border_CCCCCC/pageviews_0/viewers_0/flags_0/" alt="Flag Counter" border="0"></a>
