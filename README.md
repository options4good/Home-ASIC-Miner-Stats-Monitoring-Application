<h1>Home ASIC Miner Stats Monitoring Dashboard</h1>
Home ASIC Miner Stats Monitoring Dashboard Application for: Bitaxe, NerdQaxe, Lucky Miner, Avalon Q, Avalon Nano &amp; More. A perfect way to view stats for all of your home miners at one place. I hope I can contribute with this small project to the community and many of you will enjoy my creation. The dashboard application supports and can receive and display data from Bitaxe, NerdQaxe, Lucky Miner and Avalon home miners.<br><br>

<img width="2121" height="1019" alt="minerdashboardv222" src="https://github.com/user-attachments/assets/450ee28c-1a03-4d67-9f15-0c8aeeb9e237" />

<h2>What are the current features?</h2>

<h3>Global Status section:</h3>
<b>Total =</b> the total hashrate combined of all currently added and running miners.<br>
<b>Online =</b> how many miners are present out of all that were added in the configuration.<br>
<b>Date and Time Stamp =</b> to display the current date and time.<br>
<b>Version =</b> the version number of the application currently installed.<br><br>

<h3>Performance section:</h3>
<b>Miner =</b> the list of available miners added in the configuration plus 'workmode' indicator for Avalon miners.<br>
<b>Hashrate =</b> displays the current hashrate the miner is hashing.<br>
<b>Efficiency =</b> the the efficiancy value of the miner. The formula is: hashrate/DC wattage = efficiency (J/Th or W/Th).<br>
<b>Temp Asic/VR =</b> the temperature of the ASIC chips and the Voltage regulator.<br>
<b>Power Volt/DC/AC =</b> Input power from PSU in voltage, DC power the unit uses in wattage and AC power (at wall outlet).<br>
<b>Asic Volt/Freq =</b> the millivoltage value of each Asic chip and what frequency it is operating on<br>
<b>Fan =</b> the percentage of speed the the cooling fan is running at and the RPM value. (Avalon products do not provide exact RPM value, only percentage).<br><br>

<h3>Mining section</h3>
<b>Miner =</b> the list of available miners added in the configuration.<br>
<b>Uptime =</b> the time elapsed since the miner has been monitored by the dashboard application.<br>
<b>Best Diff All-time =</b> the highest difficuly that the miner has ever achieved. (Avalon products do not provide this value).<br>
<b>Best Diff Session =</b> the highest difficulty that the miner achieved since it was last powered on.<br>
<b>Accepted/Rejected =</b> the number of submitted shares that were accepted and rejected by the pool the miner is mining to.<br>
<b>Pool Diff =</b> the difficulty level the miner is submitting shares to the pool. (Avalon, Bitaxe and Lucky Miner products do not provide this number).<br>
<b>Blocks =</b> the number of blocks the miner has found.<br><br>



<h2>What are the upcoming features?</h2>
Continue checking the application for possible issues, adding version number, test application on other OS like Windows. Other than these:<br>
I am opened for feedback and future requests to enhance the capability of this application. Please do not hesitate to write up an issue if you notice anything not working properly. Alternatively you can reach out via Reddit: https://www.reddit.com/r/Options4Good/<br><br>

<h2>Installation & Start</h2>
<b>Linux Dependencies</b><br><br>
In the terminal perform the below command:<br><br>

```bash
sudo apt update && sudo apt install python3 python3-pip python3-venv -y
```

Download the latest dgbnodemonitor.py file from the "Releases" section: https://github.com/options4good/Home-ASIC-Miner-Stats-Monitoring-Dashboard/releases<br><br>
Start the application from the terminal running the below command:

```bash
python3 minerdashboard.py
```

<br>

<h4>Donations are possible to make and highly appreciated via crypto payments:</h4>
<b>DGB</b> wallet address:&nbsp;&nbsp;DEkZrJo1BHdiqnQq1XQSWGymEcDWGAWwZs<br>
<b>DOGE</b> wallet address:&nbsp;&nbsp;DKZ9sv4VoTiQQdwi7VY25573UfpQqZJfYf<br>
<b>LTC</b> wallet address:&nbsp;&nbsp;MJw3XHpR65Ec8rKEBthK5Dnvcy1CixYGTa<br>
<b>BCH</b> wallet address:&nbsp;&nbsp;bitcoincash:qq66dg3vhczrqf4zy4kxje3c45vz47khsufsludxcc<br><br>
Thank you.
<br><br>
