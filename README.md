# MDTNet: Multi-scale Deformable Transformer Network with Fourier Space Losses Toward Fine-scale Spatiotemporal Precipitation Nowcasting
##  Problem Statement
-- Solving the Blurry Prediction Problem in Precipitation Nowcasting through Frequency Domain Analysis

![Fig. 1. Illustrative visualizations of the blurry prediction problem from the
frequency domain. (a), (b), (c) are the ground-truth sampled echo image, the
predicted coarse and blurry echo image by state-of-the-art ConvLSTM [1],
and our predicted crisp echo image (1 hour prediction), respectively. (d), (e),
(f) are the corresponding power spectrums. (g) is the radially averaged power
spectrum. In Fig. 1 (e), only low frequency part in the middle of the spectrum
is close to the ground-truth while high frequency part is almost completely
lost. In Fig. 1 (g), there is severe high frequency component discrepancy
between the blurry prediction result and ground-truth. Remarkably, as shown
in Fig. 1 (f) and (g), the spectrum of our prediction result contains richer
and more fidelity high-frequency content, and the high-frequency part of
the radially averaged power spectrum is also greatly improved, becoming
consistent with the ground-truth.](https://github.com/zzcd1/Multi-scale-Deformable-Transformer-Network-with-Fourier-Space-Losses/blob/main/visualizations/fig1.jpg)
As shown in , the real-world long-term strong rainfall circumstances’ echo images are enriched in details and complicated in patterns, exhibiting informative and intricate high-frequency component distribution in the frequency domain. To introduce analysis of the blurry problem in precipitation nowcasting from the Fourier space, we give an illustrative visualization. Fig. 1 (a), (b), (c) show the ground-truth sampled echo image, the predicted coarse and blurry echo image by state-of-the-art ConvLSTM, and our predicted crisp echo image, respectively. Fig. 1 (d), (e), (f) are corresponding power spectrums calculated from the 2D discrete Fourier transform (DFT). Fig. 1 (g) shows the radially averaged power spectrum (RAPS). Note that some studies have explored analytical models to describe this spectral fluctuations in atmosphere. In Fig. 1 (e), it is obviously that only low frequency part in the middle of the blurry image’s spectrum is close to the ground-truth while high frequency part is almost completely lost. In Fig. 1 (g), there is severe high frequency component discrepancy between the blurry prediction result and ground-truth.




Code is coming.

![living](visualizations/38.gif)
![living](visualizations/57.gif)
![living](visualizations/772.gif)
![living](visualizations/988.gif)


<a href="https://info.flagcounter.com/WxS9"><img src="https://s11.flagcounter.com/count2/WxS9/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_10/viewers_0/labels_0/pageviews_0/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
