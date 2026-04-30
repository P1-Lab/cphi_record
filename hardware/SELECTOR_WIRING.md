<div>

<h3>WIRING SPEC: ROTARY SELECTOR</h3>
<p><strong>3P3T MECHANICAL SWITCH MAPPING | PROVISION1 LABORATORY</strong></p>

<p>
This mapping vitrifies the VGL-1 logic into the physical selector. Each position engages a discrete component sub-network, modifying the 36V signal path in real-time without latency or code.
</p>

<p><strong>Switch Topology: 3P3T (3 Poles, 3 Positions)</strong></p>

<table>
<tr>
<th>POS</th>
<th>POLE 1 (Input/Buffer)</th>
<th>POLE 2 (Kernel Filter)</th>
<th>POLE 3 (Bias/Drive)</th>
</tr>

<tr>
<td>1</td>
<td>Direct Source-Follower</td>
<td>Bypass (Flat)</td>
<td>Unity Gain</td>
</tr>

<tr>
<td>2</td>
<td>10.2kΩ Load (U47_T)</td>
<td>15.6kHz Sallen-Key</td>
<td>-1.2V Asymmetric Bias</td>
</tr>

<tr>
<td>3</td>
<td>Gyrator In (4038_R)</td>
<td>12.5kHz Roll-off</td>
<td>Inductor Hysteresis On</td>
</tr>
</table>

<p><strong>Haptic Mandate</strong></p>
<p>
The selector MUST be a shorting switch to prevent DC thumps during the 36V rail transition.
Use a heavy-action knurled brass knob to ensure intentional engagement.
</p>

</div>
