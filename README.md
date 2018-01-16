CONTRADIS is a software package that is built for the purpose of analyzing the experimental readings obtained from various methods that have been used by the previous studies in the field of contaminant transport in soils. There are different methods that use different parameters to study the flow of different ions/ contaminants through a given sample of soil. This package demonstrates two of those methods, namely, Through Diffusion technique and Half-Cell Method.  
This software is also capable of using the contaminant transport data from experiments and predicting the diffusion and linear sorption parameters of the soils, as used in Fick's second law. The software is verified on the synthetic data obtained from calculated concentration values as an input data.  

### Screenshots
Here are a few screenshots that display some demo results for CONTRADIS.
<div align="center" style="margin: 20px">
  <img src="https://github.com/CONTRADIS/contradis.github.io/raw/master/screenshots/HC.jpg">
  <img src="https://github.com/CONTRADIS/contradis.github.io/raw/master/screenshots/TD.jpg">
</div>

### Publications
This software was used to get results for the following studies:
 - Partha Das, Man Parvesh SR and Bharat TV, [“Experimental analysis of salt diffusion in compacted clays by Through Diffusion and Half-Cell technique”](http://manparvesh.com/papers/3.%20IGC_2016_paper_350.pdf), [Indian Geotechnical Conference IGC 2016 (15-17 December 2016, IIT Madras, Chennai, India)](http://igschennai.in/IGC2016_IIT_Madras/)
 - Partha Das, Man Parvesh SR and Bharat TV, [“Salt Diffusion in Compacted Plastic Clay: Experimental and Theoretical Evaluation”](http://manparvesh.com/papers/SALT%20DIFFUSION%20IN%20COMPACTED%20PLASTIC%20CLAY.pdf), [International Conference on Soil and Environment (22-23 July, 2016)](http://igsbangalore.com/SE2016/)

### Technical details
The software is built using pure Java, with the [Standard Widget Toolkit](https://www.eclipse.org/swt/) as the GUI library. Inputs from Excel sheets are taken using the [POI library](https://poi.apache.org/) and charts are displayed using [SWT chart](www.swtchart.org/). Modified versions of algorithms like Glowworm swarm optimization and Particle swarm optimization were used to obtain proper results.

### Development history
- Earlier, this software was built using the .NET framework by me. The details of the first version and all the information related to the related theory and experiments, etc., can be found in [my Bachelor's thesis](https://github.com/CONTRADIS/contradis.github.io/raw/master/report.pdf). 
- Later, it was rewritten in Java from scratch and the incomplete functions were added. After completion of this version, the [aforementioned studies](#publications) were carried out using the package.

### References
Please check the [report](https://github.com/CONTRADIS/contradis.github.io/raw/master/report.pdf).

### Tags
* Java
* SWT
* PSO
* GSO
* Cross-platform
* POLLUTE
* Contaminant Transport
* POI (for taking input from Excel) 

---
**Note:** This page is for information display only. The code is not open-source.
