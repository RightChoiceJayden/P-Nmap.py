# P-Nmap.py
<h2>Description</h2>

Welcome to the Nmap Port Scanner project! This repository contains a Python-based Nmap port scanner designed to perform efficient network scanning and analysis. The project is developed using Visual Studio Code and leverages the nmap library to interact with Nmap, a powerful network scanning tool.
</b>

<h2>Features</h2>

- <b>Host Discovery:</b> Identify live hosts within a specified IP range.

- <b>Port Scanning:</b> Scan for open ports on a target host.

- <b>Protocol Detection:</b> Determine the protocol running on open ports(UDP/TDP).

- <b>OS Detection:</b> Identify the operating system of the target host.
</b>

## Languages

- <b>Bash</b>
- <b>Python</b>

## Prerequisites

- <b>Python 3.x</b>
- <b>Nmap</b>
- <b>Visual Studio Code</b>
- <b>Code Runner (Visual Studio Code extension)</b>

## Setup

"import" statement used to import modules or libraries (bigger collections of code that can provide additional functuality to the script we are writing). We use this first to import nmap

![Line1](https://github.com/RightChoiceJayden/P-Nmap.py/assets/157855848/e6cedc39-b8cc-4fc6-9eba-dc66d1fd30a6)

Create an instance of the "nmap.PortScanner" class. We then assign it the variable "nm". (We will be calling it later on in the script)

![Line3](https://github.com/RightChoiceJayden/P-Nmap.py/assets/157855848/08a9aee6-888b-4f27-802e-d62b57539844)

We then create two more variables in these two lines. One being "target" the other being "options". "target" defines what our target IP is (the IP we are using is the one provided by nmap themselves to run practice tests on. Please remember, nmap is active recognizance and is illegal to run on someones IP without permission). "options" is defining how we will use nmap. We will be using the -sV switch (enables version detection, which allows users to gather information about a port's service) and the -sC switch (executes a scripted scan using the default category of scripts in the Nmap Scripting Engine)

![Line5](https://github.com/RightChoiceJayden/P-Nmap.py/assets/157855848/521ee24f-9e1c-44a7-b0cb-d47e0532170d)

This line of code is calling the scan method on an instance of the nmap.PortScanner class. It takes two arguments we priviously defined. "target" and "arguments"(which we made = to "options")

![Line8](https://github.com/RightChoiceJayden/P-Nmap.py/assets/157855848/945e4033-22b3-4820-80ca-5f9162fc1e81)


![Line10](https://github.com/RightChoiceJayden/P-Nmap.py/assets/157855848/82ec2654-643c-4e32-ba13-906434a4ba7a)
