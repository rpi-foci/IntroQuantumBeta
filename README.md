<!-- [<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/rpi-foci/IntroQuantumBeta.git) -->

[![Env Badge](https://img.shields.io/endpoint?url=https://api.qbraid.com/api/environments/valid?envSlug=rpi_qu_8b7d9z&label=Launch+on+qBraid&labelColor=lightgrey&logo=rocket&logoSize=auto&style=for-the-badge)](http://account.qbraid.com?gitHubUrl=https://github.com/rpi-foci/IntroQuantumBeta.git&envId=rpi_qu_8b7d9z)


# Introduction to Quantum Computing Workshop

This is the Beta version of a Workshop to step participants through
running their first program on a quantum computer.  In this workshop,
we will:

   1) Create a gBraid account (if needed).
   2) Launch qBraid from this GitHub repository
   3) Log on to IBM's Quantum Cloud
   4) Load the runtime Jupyter lab, and configure the Qiskit Runtime
   5) Load HelloBell Jupyter lab and run a simple measurement of a Bell state
   6) Run the same program, but with unentangled qubits
   7) Discuss and compare results

For those interested, and time permitting, instructions for a local installation
of Python (miniconda), and Qiskit are provided.

## Log in to qBraid

Before launching qBraid, create a qBraid account at [https://www.qbraid.com](https://www.qbraid.com).  This can
be created using your RPI email address, or another address.  If you already have a qBraid account login.

## Launch qBraid

Click the "LAUNCH ON QBRAID|RPI QUANTUM COMPUTER WORKSHOP" button.

This will launch qBraid.  *Note, you may want to launch in a separate tab or window to keep these instructions.*

qBraid will take a few moments cloning the git repository and setting up your workspace.

## Open these files in qBraid

Along the bottom of your qBraid screen you will see some files and folders.  Click the folder
labeled "IntroQuantumBeta".   This will open a launch window on the right.

Select the "Free 2vCPU 4GB RAM" option, and launch the lab.  Note this might take awhile to start,
and you may need to launch the started lab under "Launch Lab".

## Load the lab's Python Kernel

Once the lab is launched, EWS tab on the upper right corner.  This will show the Default kernel,
and the "RPI Quantum Computing Workshop" kernel.

Click the drop down for the RPI kernel, and add it.  This will load the required Python packages,
including Qiskit.

## Configure Qiskit Runtime

Click "Runtime.ipynb" on the left.  This will open the Jupyter lab.  On the top right of the
lab is the current Python kernel.  Make sure it is: "Python 3 [rpi-quantum-comp]"  If not, click
and select the kernel.

Follow the lab for instructions on configuring the Qiskit runtime.

## Run the HellBell program

After the runtime is configured, click on "HelloBell.ipynb".  Ensure the "rpi-quantum-comp" kernel is
being used.

Follow the instructions in the lab to run (your first?) quantum computer program on RPI's Quantum System One.


This repository is:

https://github.com/rpi-foci/IntroQuantumBeta.git


