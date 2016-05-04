# The Leading Edge Tutorial: 
#	Full Waveform Inversion

<strong>What is full waveform inversion?</strong> How does it work? Is it of any benefit to geophysicists?

In this repo we explore the most basic concept of FWI, to inspire personal development of more useful FWI algorithms. The code contained here is a "toy" FWI algorithm meant to be used on very simple 3D synthetic data.

This algorithm will be published in SEG's The Leading Edge geophysical tutorial series in August of 2016.

To run this stuff you'll need Julia v0.4, and the Julia package Seismic. <strong>Here's how you install and run the project:</strong>
<ul>
	<li>sudo apt-get install julia</li>
	<li>julia > Pkg.add("Seismic")</li>
	<li>git clone git@github.com:gganssle/tle_fwi.git</li>
	<li>cd tle_fwi/fwi</li>
	<li>julia</li>
	<li>include("conv_FWI.jl")</li>
	<li>enjoy</li>
</ul>

Please contact GRAM with any questions at <a href="https://gra.m-gan.sl">gra.m-gan.sl</a>, or on Twitter <a href="https://twitter.com/grahamganssle">@GrahamGanssle</a>.
