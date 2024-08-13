<h1>Bulk Subnet Pinger - Fping</h1>

<li>This script will use a source txt document and run fping -g | grep alive for each inserted subnet.</li

<li>The output of this script will only show Alive IPs, no ICMP host timeouts or other data will be displayed.</li

<h2> Operational instructions </h2>

<ol>
<li> Open subnets.txt and insert the subnets you wish to check. Accepted format is: </li>
<b>
<li> subnet 1 </li>
<li> subnet 2 </li>
<li> subnet 3 </li>
</b>
<li> Make sure it's saved by pressint CTRL + S (May vary on text editor) </li>
<li> Open a terminal and run python check_alive_hosts.py </li>
<li> Results will be added to "alive_hosts.txt". </li>
</ol>

<h2> Dependencies </h2>

<li>A Linux Terminal (Native or WSL)</li>
<li><b>Fping</b> - Can be installed via this command on Ubuntu:</li>
<li>sudo apt install fping</li>
<li><b>Python</b>. or the </b>Python3</b> package - Can be installed via this command on Ubuntu:</li>
<li>sudo apt install python</li>
<li>OR
<li>sudo apt install python3</li>

If there are any adjustments or neccesary changes, please let me know.