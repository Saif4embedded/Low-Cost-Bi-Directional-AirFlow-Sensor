![alt_text](images/sch_1.png "image_tooltip")


[DemoVideo](https://www.youtube.com/watch?v=aSJlc7u3Vi4)

**Introduction:**

In emergencies like this, finding an air flow sensor for your ventilator system can be challenging. This sensor can at least detect the presence of air flow and its direction and combined with a bit of DSP and proper calibration linear air flow sensing can be achieved. I hope this will help someone somewhere make a system that will save lives.

**Working Principle:**

Without going into much details, this circuit works by heating both 1N4148 Diodes with forward biasing. When the air blows across the diodes, differential voltages are generated due to complex semiconductor magic. The LM358 circuit amplifies the small voltage to a level where it can be used by your arduino or DSP circuit to determine air flow.

**Sensor Tube:**

The sensor tube is made out of a 10cc syringe. The diodes are placed on both sides of the tube and a flow separator is used to get differential reading due to direction of flow.

Modified syringe:



<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/Low-Cost1.jpg). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/Low-Cost1.jpg "image_tooltip")


<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/Low-Cost2.jpg). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/Low-Cost2.jpg "image_tooltip")


Flow separator:



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/Low-Cost3.jpg). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/Low-Cost3.jpg "image_tooltip")




<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/Low-Cost4.jpg). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/Low-Cost4.jpg "image_tooltip")


**Dimensions:**



<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/Low-Cost5.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/Low-Cost5.png "image_tooltip")


**Prototype Circuit:**



<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/Low-Cost6.jpg). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/Low-Cost6.jpg "image_tooltip")


**Note:**



*   If you make this circuit on a breadboard, take care of parasitic capacitance, contact resistance and ground loops.
*   Both diodes (1N4148) and 10R 1W resistor will heat up. This is normal.
*   External Temperature Compensation may be needed.
*   Depending on the ambient temperature, about 10 seconds of Warm up time needed.
*   Noise shielding is necessary on the final circuit.

**Use it at your own risk. Good Luck.**
