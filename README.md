# Linux
This is a file that used to remind me of first time building a Linux system with Python and try to make it work for AIMO, with AlphaGeometry

## 1 Basic usage of Linux:

Install :
`sudo apt ...`

Update system: 
 `sudo apt update`
 
---

Install Python related 

Start a virtual environment: 
`virtualenv -p /usr/bin/python3.10 venv`
This is a order that used to create virtual environment based on specific environment: here is Python 3.10 in root `/usr/bin/python3.10` and the name of the new environment is called `venv`

Then, to activate it, we use `source venv/bin/activate`

Check the Python in the system: 
`ls -l /usr/bin/python*`
