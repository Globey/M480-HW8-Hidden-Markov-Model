M480-HW8-Hidden-Markov-Model
============================

<b>Create a Hidden Markov Modelof a person like I did in Lecture 22. Be as creative (or not) as you want. </b>

<p>
Jake, who is from Vermont, has just won the $600 Million PowerBall jackpot. He's decided that he only likes 4 states and that he's going to spend the rest of his life traveling between those states and only those states. At midnight he decides which state he wants to travel to next (he can also choose to stay in his current state) and of course he makes haste for that state.  In the morning he texts his mom what activity he's going to do for the day. His mother tries to guess which state he's in based on what activity he engages in for the day. The transition, emission, and initial probabilities are outlined below.
</p>

<b>States:</b> Coloarado, Hawaii, Vermont, California (get it?)

<b>Emissions:</b> Skiing, Swimming, Sunbathing, Hiking, Fishing <br>

<b>Transition Probabilities:</b> <br>
Colorado ---> Colorado: 75% <br>
Colorado ---> California: 10% <br>
Colorado ---> Hawaii: 15% <br>
Hawaii ---> Hawaii: 90% <br>
Hawaii ---> Vermont: 7% <br>
Hawaii ---> Colorado: 2% <br>
Hawaii ---> California: 1% <br>
Vermont ---> Vermont: 30% <br>
Vermont ---> California: 60% <br>
Vermont ---> Hawaii: 10% <br>
California ---> California: 80% <br>
California ---> Colorado: 15% <br>
California ---> Vermont: 5% <br>

<b>Emission Probabilities:</b>
<table>
	<tr>
		<td>State</td>
		<td>Skiiing</td>
		<td>Swimming</td>
		<td>Sunbathing</td>
		<td>Hiking</td>
		<td>Skateboarding</td>
	</tr>
	<tr>
		<td>Colorado</td>
		<td>0.50</td>
		<td>0</td>
		<td>0.15</td>
		<td>0.25</td>
		<td>0.10</td>
	</tr>
	<tr>
		<td>Hawaii</td>
		<td>0</td>
		<td>0.60</td>
		<td>0.25</td>
		<td>0.10</td>
		<td>0.05</td>
	</tr>
	<tr>
		<td>Vermont</td>
		<td>0.30</td>
		<td>0</td>
		<td>0</td>
		<td>0.55</td>
		<td>0.15</td>		
	</tr>
	<tr>
		<td>California</td>
		<td>0.20</td>
		<td>0.25</td>
		<td>0.30</td>
		<td>0</td>
		<td>0.25</td>
	</tr>
</table> <br>


<b>Initial Probabilities:</b>
<table>
	<tr>
		<td>State</td>
		<td>Colorado</td>
		<td>Hawaii</td>
		<td>Vermont</td>
		<td>California</td>
	</tr>
	<tr>
		<td>Probability</td>
		<td>0</td>
		<td>0</td>
		<td>1</td>
		<td>0</td>
	</tr>
</table> <br>

<p>
<b>Graphical Representation of the Model:</b><br>
Nodes: Colorado = 0, Hawaii = 1, Vermont = 2, California = 3.<br>
<img src="https://dl.dropboxusercontent.com/u/66800298/M480_HW8_HMM_Graph.png" alt="Graphical Representation">
</p>


<b>For computational examples please see Sage Worksheet.</b>