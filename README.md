# HTB-swagshop
Documentation for the Swagshop box

## How to execute the script
1. Edit the `reverse_shell.php.jpg` file to include your own ip (`ifconfig`) and a nice port (eg. `10365`)
2. Make sure the three files (`37977.py`, `reverse_shell.php.jpg` and `automated-exploit.py`) are in the same folder
3. Run `python automated-exploit.py`
4. Open another terminal and run `nc -v -n -l -p [your_port]` (eg. ` nc -v -n -l -p 10365`)
5. When the script asks, make sure netcat is listening, and press enter
6. The script should hang, and the netcat should have a shell

## Can I run this multiple times?
Yes.

## How does it work?
By using a flute to tame the python.
