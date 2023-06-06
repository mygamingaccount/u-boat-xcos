# Controls

In the current early version of this model the controls are rudimentary sliders that do not support labels. Only way to tell them apart is by their ranges. While it is not ideal, it is sufficient to let us control the simulation in real time.

<table>
<tr>
<td><img src="./control_batt.png" ></td>
<td>Battery voltage. Recommended range: 105-170V to simulate driving and charging at different states of charge</td>
</tr>
</table>

<table>
<tr>
<td><img src="./control_clutch.png" ></td>
<td>Clutch<br>
0 = off, any other value connects the propeller to the motor</td>
</tr>
</table>

<table>
<tr>
<td><img src="./control_feldregler.png" ></td>
<td>Field rheostat<br>0 = full field, shunt field current diminishes as this value is increased</td>
</tr>
</table>

<table>
<tr>
<td><img src="./control_FR.png" ></td>
<td>FR, forward reverse switch.<br>
1 = forward<br>
0 = off<br>
Reverse running is not supported by the propeller model used</td>
</tr>
</table>

<table>
<tr>
<td><img src="./control_MSP_BPS.png" ></td>
<td>Maneuver switch preset. <br>
5 = MP/BS (220V)<br>
4 = off<br>
3 = MP/BP (110V)<br>
2 = off<br>
1 = MS/BP (55V)<br>
</td>
</tr>
</table>

<table>
<tr>
<td><img src="./control_D.png" ></td>
<td>Diesel fuel handle.<br>
Sets fuel amount to achieve the desired RPM when surface running. Governor limits fuel to the selected RPM when the clutch is off</td>
</tr>
</table>
