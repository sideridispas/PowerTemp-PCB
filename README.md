# PowerTemp-PCB
Two separated functions of the board, depending on which side is populated:
<ul>
	<li>Side A: PowerSupply
		Takes a DC Voltage (max 30V) as input and gives a fixed stable 5V output. Also has "wrong connection" protection with diodes
		Parts: LM7805CT, 0.33uF & 0.1uF Capacitors, RS1A Diodes, 2-Pin terminals
	</li>
	<li>Side B: Temperature
		Facilitates a DS18B20 sensor and two 3-Pin terminals
	</li>