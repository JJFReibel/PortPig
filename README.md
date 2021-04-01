# PortPig
**Lists open ports in the console**

Download script using git or directly from GitHub.

Download Python 3, latest version (3.10 at time of writing).

From console (Unix or Linux shells compatible with Shell, Bash, Z Shell...), navigate to the desired directory using cd [Path].

Enter python3 PortPig.py and press Enter or Return.

Enter the desired IP address at the prompt.

Open ports will be listed. Hold Control and press C (Ctrl+C) to stop the script.

In PortPig.py, modify the value of t for timeout, as number in seconds. Default is 1.
A value that is too small will check too quickly and not list all open ports, while a larger number will take too long.
t=0.1 works about as well as 1 with decent internet.
Modify r for port range upper limit. Default is upper max limit for TCP.
For custom range with lower limit, change range(r) to range(i, r), where i is the lower range.
