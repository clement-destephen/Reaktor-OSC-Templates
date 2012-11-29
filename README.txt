Reaktor OSC Templates
=====================

Ensembles/Instruments for Reaktor 5.8 and Lemur/TouchOSC.

~ What is the goal ?

The goal of those ensembles is to provide the builder a set of macros handling the most common OSC messages coming from iPad apps Lemur (Liine) and TouchOSC (Hexler).


~ What is included ?

You will find instruments working with default Lemur/TouchOSC templates. Those instruments contain macros for different types of objects (fader, knob, array, drumpad, keyboard…)


~ How is it using Reaktor 5.8 OSC capabilities ?

It demonstrates a common use of most OSC objects :
- OSC receive/send
- OSC receive array
- embedded OSC in panel objects (buttons,...)


~ Main features:

- every object is available as a macro and can thus be re-used.
- Both IC and Direct outputs are available for most objects
- Drumpads and Keyboards output data through internal MIDI. The best way to connect them is to go to the target instrument properties and select the template instrument as an internal source.
- all scalings can be saved as snapshots.
- mapping configurations are saved at the ensemble level.

Q&A
===

~ How do I setup my Reaktor/iPad to use OSC ?

A short description is given inside the instruments help (instrument properties > info). However, if you need more help please refer to Native Instruments Knowledge Base :

How to set up TouchOSC with REAKTOR 5.8 (MAC)
http://www.native-instruments.com/knowledge/questions/1269

How to set up TouchOSC with REAKTOR 5.8 (PC)
http://www.native-instruments.com/knowledge/questions/1279

How to set up Lemur with REAKTOR 5.8 (MAC)
http://www.native-instruments.com/knowledge/questions/1281

How to set up Lemur with REAKTOR 5.8 (PC)
http://www.native-instruments.com/knowledge/questions/1287

How to map MIDI and OSC controllers in REAKTOR 5.8
http://www.native-instruments.com/knowledge/questions/1297

~ My connection seems to work, but pages won´t change when I change them on the iPad…

It is a limitation of the default templates, both for Lemur and Touch OSC. However it is possible to do it by modifying the templates and the Reaktor instruments accordingly.



Happy building,

Clément Destephen

Any comment or suggestions ? Feel free to write me an email :
cdestephen at gmail dot com

====================================================================================================

Reaktor OSC Templates are Copyright 2012, Clement Destephen.

This file is part of Reaktor OSC Templates.

Reaktor OSC Templates is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

Reaktor OSC Templates is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with Reaktor OSC Templates.  If not, see <http://www.gnu.org/licenses/>.

====================================================================================================