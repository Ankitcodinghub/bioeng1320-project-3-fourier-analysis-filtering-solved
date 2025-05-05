# bioeng1320-project-3-fourier-analysis-filtering-solved
**TO GET THIS SOLUTION VISIT:** [BIOENG1320 Project 3-Fourier Analysis & Filtering Solved](https://www.ankitcodinghub.com/product/bioeng1320-project-3-fourier-analysis-filtering-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101505&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;BIOENG1320 Project 3-Fourier Analysis \u0026amp; Filtering Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Computing the Fourier Transform of a biological signal: The Fourier Transform is perhaps the most popular technique for analyzing biological signals. It allows the signals to be visualized in the frequency domain via spectra. From Lecture, the Fourier Transform is given as follows:

𝑋(𝜔)=∫∞ 𝑥(𝑡)𝑒−𝑗𝜔𝑡𝑑𝑡. (1) −∞

In general, the biological signal 𝑥(𝑡) is too complicated to determine its Fourier Transform 𝑋(𝜔) analytically (i.e., by pencil and paper). A computer must therefore be used. However, the Fourier Transform is a continuous function and an infinite integral. As a result, it cannot be determined with a computer! Three modifications are necessary for computer-based solution. First, the integral is approximated using rectangular pulses of width 𝑇 to convert it to a sum as follows:

𝑋(𝜔) ≈ ∑∞ 𝑥(𝑛𝑇 )𝑒−𝑗𝜔𝑇 𝑛𝑇 . (2) 𝑛=−∞ 𝑠 𝑠 𝑠

Then, the signal is assumed to be non-zero within the finite time interval [0, (𝑁 − 1)𝑇 + 𝑇 ] so 𝑠𝑠

</div>
</div>
<div class="layoutArea">
<div class="column">
that the infinite sum becomes a finite sum as follows:

𝑋(𝜔) = ∑𝑁−1 𝑥(𝑛 𝑇 )𝑒−𝑗𝜔𝑇 𝑛𝑇 .

</div>
</div>
<div class="layoutArea">
<div class="column">
(3) Finally, the continuous variable 𝜔𝑇 is sampled at intervals of 2𝜋 over the range of [0,2𝜋] to

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑛=0 𝑠 𝑠 𝑠

𝑁

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑠

transform the continuous function to a discrete function as follows:

𝑁−1 −𝑗2𝜋𝑘𝑛

𝑋[𝑘] = 𝑋(𝜔)| 2𝜋 = ∑ 𝑥(𝑛 𝑇 )𝑒 𝑁 𝑇 , 𝑘 = 0,1, … , 𝑁 − 1. (4)

</div>
</div>
<div class="layoutArea">
<div class="column">
𝜔𝑇= 𝑘 𝑠𝑁

</div>
<div class="column">
𝑛=0 𝑠 𝑠

</div>
</div>
<div class="layoutArea">
<div class="column">
For convenience, 𝑇 is set to unity to arrive at the “Discrete Fourier Transform (DFT)” as follows: 𝑠

𝑁−1 −𝑗2𝜋𝑘𝑛

𝑋[𝑘] = ∑𝑛=0 𝑥[𝑛]𝑒 𝑁 , 𝑘 = 0,1, … , 𝑁 − 1. (5)

The DFT is a discrete function and a finite sum. As a result, it is amenable to computer-based solution for a given “sampled signal” 𝑥[𝑛].

The Fast Fourier Transform (FFT) is a family of algorithms for efficient computation of the DFT. These algorithms, in particular, are widely used in biological signal processing.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
Due: 5:00p, April 20, 2022 (via Canvas)

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑠

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
The purpose of this problem is to learn how to use the all-important, built-in fft function.

<ol>
<li>Figure 1 shows a continuous-time signal 𝑥(𝑡). The Fourier Transform of this signal can be
determined analytically and is 𝑋(𝜔) = 12 (𝑠𝑖𝑛(6𝜔))2 𝑒−𝑗𝜔12 . Plot the magnitude and phase 6𝜔

spectra over an 𝜔 range of [0, 𝜋] using a fine sampling interval. This exact result will be needed to compare the FFT results to be computed below.

Figure 1
</li>
<li>Take samples of 𝑥(𝑡) at 𝑇 = 1 to define 𝑥[𝑛] as a vector of 25 samples in length using the 𝑠
triang function. Use the fft function to compute the DFT of this signal for 𝑁 = 256. Plot the DFT magnitude and phase spectra. Note that the x-axis should range over an 𝜔𝑇 of [0,2𝜋].

How does this result compare to the analytical result? What is the highest frequency shown by the FFT?
</li>
<li>Now plot the DFT spectra of the signal for 𝑁 = 16, 32, 128. Compare all FFT plots with the analytical result. For what values of 𝑁 are the DFT samples (mostly) valid? Which values of 𝑁are,forthemostpart,indicativeofthetruespectralcontentofthesignalandwhy? How can 𝑁 be chosen in practice without knowledge of the analytical result?</li>
<li>Use pair 17 in Table 7.1 (Fourier Transform pairs) and properties in Table 7.2 (Fourier Transform properties) to derive 𝑋(𝜔) in question 1. (Hint: see Practice Exam 1!)</li>
<li>Compute the DFT for the clean action potential signal from Project 1. Plot the DFT magnitude and phase spectra. Note that 𝑇 = 1 in the previous questions. This simplification turned out
to make frequencies for 𝑥(𝑡) and 𝑥[𝑛] the same values! However, in general, 𝑇 is not unity. 𝑠

For example, 𝑇 = 0.0796 ms for the action potential signal. So, such simplification no longer 𝑠

holds. From the red font, it can be inferred that the highest frequency shown by the FFT in units of Hz is half the “sampling frequency” (i.e., 1/(2*0.0796)=6.2814 kHz in this case). So, make sure to plot the spectra from 0 kHz to 6.2814 kHz! Do the spectra meet your expectations for the action potential signal?
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
𝑠

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
𝑠

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Designing a filter to remove noise from a biological signal: In Project 1, a filter impulse response was given, which removed the noise in the noisy action potential signal without compromising the information in the clean action potential signal. In practice, filters are not given! The purpose of this problem is to learn how to design a filter.

<ol start="6">
<li>Plot the DFT magnitude and phase spectra for the noisy action potential signal from Project 1. Compare to the corresponding plots of the clean action potential signal. This comparison may be facilitated using units of decibels. What are the main differences in the frequency- domain? Noting these differences should help in filter design.</li>
<li>Now design a filter using window-based filter design to selectively remove the noise. Use the built-in function fir1. Apply the filter to each signal while experimenting with different cutoff frequencies. Plot the selected filter impulse response and each of the filtered signals. What kind of filter was selected and what were the cutoff frequencies?
Deliverables: Submit a single pdf file containing answers to the questions, properly labeled plots, and the source code.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
