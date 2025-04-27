# cpe-325-assignment-10-solved
**TO GET THIS SOLUTION VISIT:** [CPE 325 Assignment #10 Solved](https://www.ankitcodinghub.com/product/cpe-325-assignment-10-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;72636&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPE 325 Assignment #10 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<h2>Assignment</h2>
<ol>
<li>&nbsp;Write a C program to interface the 3-dimensional accelerometer, ADXL335. Your program should sample x, y and z axes 5-times per second. Calculate the accelerations in terms of ‘g’ (Gravity of Earth) and send the samples to workstation. Samples should be sent such that they are displayed in UAH serial app as three separate lines. Please revisit the previous Lab 8 assignment to see how to use UAH serial app.</li>
<li>&nbsp;An accelerometer can be used in a car as a crash sensor to deploy airbags. When the magnitude of acceleration reaches some critical value (a crash was detected), a signal is sent to the airbag system. Modify the program from part 1 (do not remove any existing functionality), so that it calculates the magnitude using data from all three axes: 𝑀=</li>
</ol>
√𝑥<sup>2</sup>+𝑦<sup>2</sup>+𝑧<sup>2</sup>. If 𝑀 reaches the critical value of 2g, LED1 should turn on, emulating airbag deployment. SW1 should turn LED1 off, so that a new crash can be detected.

<ol start="3">
<li><strong>[50 pts]</strong> Write a C program that outputs different waveforms using DAC. It should have the following modes:</li>
</ol>
<table width="575">
<tbody>
<tr>
<td width="253"><strong>Switch Pressed </strong></td>
<td width="323"><strong>Waveform Displayed </strong></td>
</tr>
<tr>
<td width="253">None</td>
<td width="323">Sine wave:</td>
</tr>
<tr>
<td width="253">SW1</td>
<td width="323">Sawtooth wave:</td>
</tr>
<tr>
<td width="253">SW2</td>
<td width="323">Half of the amplitude of the current wave form.</td>
</tr>
</tbody>
</table>
&nbsp;

The waveforms will be viewed by connecting an oscilloscope to the output of DAC on MSP430. You should use MATLAB to create waveform lookup tables (LUTs) for the needed waveforms. These LUTs will be included as header files that are utilized by your main C program. For each signal, one period should have 512 samples and its frequency should be 25 Hz.

<h2>Bonus</h2>
<ol start="4">
<li>Read the following article about a method of quick magnitude estimation: <a href="https://dspguru.com/dsp/tricks/magnitude-estimator/">https://dspguru.com/dsp/tricks/magnitude</a><a href="https://dspguru.com/dsp/tricks/magnitude-estimator/">–</a><a href="https://dspguru.com/dsp/tricks/magnitude-estimator/">estimator/</a><a href="https://dspguru.com/dsp/tricks/magnitude-estimator/">.</a> Implement it in C and think about how you can apply it to the 3D case. Replace the sqrt-based magnitude calculation used in part 1 with the new method. Is it faster than the original one? Support your conclusion by clock measurements (see Lab 1).</li>
</ol>
&nbsp;
