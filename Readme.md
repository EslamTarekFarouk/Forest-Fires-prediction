# Data Info :
* i could find alot of useful info at this <a href =  "http://archive.ics.uci.edu/dataset/162/forest+fires">link</a>

* This dataset was first introduced in datamining paper by Paulo Cortez and An´ıbal Morais, and the data was published at at this <a href = "https://www.dsi.uminho.pt/">website</a>
 
* The forest Fire Weather Index (FWI) is the Canadian system for rating fire danger and it includes six components :

 1- Fine Fuel Moisture Code (FFMC) which  denotes the moisture content surface litter and influences ignition and fire spread

 2,3- Duff Moisture Code (DMC) and Drought Code (DC) which represent the moisture content of shallow and deep organic layers 
 
 5- Initial Spread Index (ISI) which is  is a score that correlates with fire velocity spread

 6- Buildup Index (BUI) which represents the amount of available fuel (ex.  grass and leaves)
 
* the first three components are calculated using dataset features like rain, temprature, wind and relative humidity

* ISI is calculated from wind and FFMC 

* the rest was dropped by the dataset provider the reason he has suggested : "The BUI and FWI were discarded since they are depen-dent of the previous value"

* X and Y represent a square region of  9x9 grids which represents Montesinho Natural Park

  > __The Following table was privided in the paper:__
<table id ="Attribute Description">
<thead>
  <tr>
    <th colspan="2">Attribute Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>X</td>
    <td>x-axis coordinate (from 1 to 9)</td>
  </tr>
  <tr>
    <td>Y</td>
    <td>y-axis coordinate (from 1 to 9)</td>
  </tr>
  <tr>
    <td>month</td>
    <td>Month of the year (January to December)</td>
  </tr>
  <tr>
    <td>day</td>
    <td>Day of the week (Monday to Sunday)</td>
  </tr>
  <tr>
    <td>FFMC</td>
    <td>FFMC code</td>
  </tr>
  <tr>
    <td>DMC</td>
    <td>DMC code</td>
  </tr>
  <tr>
    <td>DC</td>
    <td>DC code</td>
  </tr>
  <tr>
    <td>ISI</td>
    <td>ISI inde</td>
  </tr>
  <tr>
    <td>temp</td>
    <td>Outside temperature (in ◦C)</td>
  </tr>
  <tr>
    <td>RH</td>
    <td>Outside relative humidity (in %)</td>
  </tr>
  <tr>
    <td>wind</td>
    <td>Outside wind speed (in km/h)</td>
  </tr>
  <tr>
    <td>rain</td>
    <td>Outside rain (in mm/m2)</td>
  </tr>
  <tr>
    <td>area</td>
    <td>Total burned area (in ha) ha = 100 m<sup>2</sup></td>
  </tr>
</tbody>
</table>
