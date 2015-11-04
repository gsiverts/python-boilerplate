# Resin.io python Boilerplate

This is a simple example project for [resin.io](http://resin.io) which demonstrates a simple Hello, World program and how to install packages on the Linux OS installed on your devices.

This project uses the [Dockerfile.template](/Dockerfile.template]) to define the build and runtime environment. In the [requirements.txt](/requirements.txt]) we specify which python packages will be installed. This will be run **on the resin.io builder** and only built once for the entire fleet of devices.

[hello.py](/hello.py) is the python script that will run when the container starts **on your device**.
