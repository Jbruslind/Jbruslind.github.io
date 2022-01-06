---
layout: page
title: About
---

# <p class="message">
# </p>


## History 

The HyperRail project began in [xxxx] as a way to simplify data collection within a greenhouse / growing space, specifically hyperspectral images. The main idea is to have automated data collection at certain time intervals (days, weeks, etc) which can then be compared for time-varying properties. The system in question must meet a specified set of requirements (called "User Requirements") listed below:  

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Description</th>
      <th>Subgroup</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Area</td>
      <td>The system must be able to image a minimum area of 20' x 20' x 5'</td>
      <td>Mechanical</td>
    </tr>
    <tr>
      <td>Power</td>
      <td>The system will operate on US standard electricity (120VAC/50-60Hz)</td>
      <td>Electrical</td>
    </tr>
    <tr>
      <td>Automation</td>
      <td>The system will have automatic path planning</td>
      <td>Software</td>
    </tr>
	<tr>
		<td>Price</td>
		<td>The system's parts will cost <$2500 in total</td>
		<td>Mechanical, Electrical</td>
	</tr>
	<tr>
		<td></td>
		<td></td>
		<td></td>
	</tr>
  </tbody>
</table>

### Approach 

The simplest approach to reliable, automated data collection over a wide area is a 3D Gantry or CNC machine. These systems have been around since the 1950s and the technology is well developed. While not normally used in outdoor applications, there are existing examples of CNC machines used outdoors such as: [FarmBot](https://farm.bot/)  , [MudBot](https://www.mudbots.com/concrete-3d-printers.php), and the [Scanalyzer](https://www.lemnatec.com/customized-solutions/field-scanalyzer/). 

The Scanalyzer system in particular matches all the requirements for the HyperRail in that it can perform automated hyperspectral imaging of wide areas of land. However it exceeds the area requirement and costs much more than the price requirement (~10's to 100s of thousands).   
  
For this implementation the FarmBot was used as a model for design. It's modular design and open source hardware made it a great starting point for ideas and development. A key drawback to the FarmBot design is that it doesn't extend to the dimensions required (20' x 90' x 5') and so its structure is untested at these limits. 