# Introduction to Quantum Computing Workshop

This is the Beta version of a Workshop to step participants through
running their first program on a quantum computer.  In this workshop,
we will:

   * Request access to RPI's Quantum System One, and create an IBM Quantum Cloud account
   * Create a gBraid account and logon
   * Open qBraid from this GitHub repository
   * Launch Jupyter Labs, and install the course's kernel
   * Configure the Qiskit Runtime
   * Run HelloBell to measure a Bell State on the quantum computer
   * Run the same program, but with unentangled qubits
   * Discuss and compare results
   * Optionally install miniconda and Qiskit locally

This lab uses a hosted Jupyter Lab.  Time permitting, there are instructions for a local installation
of Python (miniconda), and Qiskit.


## Request to RPI's Quantum System One

If you do not already have a quantum computer account,
[request one now](https://webforms.rpi.edu/form/rpi-quantum-hub-access-request).

Accept the emailed invitation link, and create your [IBM Quantum Cloud](https://quantum.cloud.ibm.com).
Information needed for the Qiskit Runtime is found there.  **Do not use your RPI password.**


## Create a qBraid account, and logon to qBraid

If you have not already done so create a qBraid account at [https://www.qbraid.com](https://www.qbraid.com).  This can
be created using your RPI email address, or another address.  **Do not use your RPI password.**

Logon to qBraid.


## Launch qBraid

Click the:

<!-- [<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/rpi-foci/IntroQuantumBeta.git) -->

[![Env Badge](https://img.shields.io/endpoint?url=https://api.qbraid.com/api/environments/valid?envSlug=rpi_qu_8b7d9z&label=Launch+on+qBraid&labelColor=lightgrey&logo=rocket&logoSize=auto&style=for-the-badge)](http://account.qbraid.com?gitHubUrl=https://github.com/rpi-foci/IntroQuantumBeta.git&envId=rpi_qu_8b7d9z)

button.

This will launch qBraid.  **Note, you may want to launch in a separate tab or window to keep these instructions.**

qBraid will take a few moments setting up your workspace, and cloning this Git repository.


## Launch Jupyter Lab and Install the Course's kernel

Once qBraid is ready:

Under ``Launch Lab'' select the ``Default Workspace'' and click ``Next >''.

Select ``Free 2vCPU 4GB Ram''.  You may have to start the
lab, or it may already be running.  Click the ``Launch Lab'' button.

Once the lab is launched click the EWS tab on the upper right corner.  This will show the Default kernel,
and the ``RPI Quantum Computing Workshop'' kernel.

Click the drop down for the RPI kernel, and ``Add'' it.  This will load the required Python packages,
including Qiskit.

While we will not be doing this today, the ``+ ADD'' link at the top can be used to add more environments, such as PennyLane.


## Open Class Lab Folder

On the left side of Jupyter Lab there should be a ``IntroQuantumBeta'' folder. Double-click it.


## Configure Qiskit Runtime

We are now ready to do some programming.

Double-click ``Runtime.ipynb'' lab on the left.

On the top right of the lab page the current Python kernel name is displayed.  Make sure
it is: "Python 3 [rpi-quantum-comp]" If not, click and select the
course's kernel.

Follow the lab for instructions on configuring the Qiskit runtime.  This will require both an API token,
and a Cloud Resource Name (CRN) from [IBM Quantum Cloud](https://quantum.cloud.ibm.com).


## Run the HellBell program

After the runtime is configured, open "HelloBell.ipynb" (listed on the left).  Ensure the "rpi-quantum-comp" kernel is
being used.

Follow the instructions in the lab to run (your first?) quantum computer program on RPI's Quantum System One.


## Install Python and Qiskit Locally

qBraid hosts a Jupyter Hub, a Jupyter Lab for running Python programs.  But you can install Python,
Jupyter Lab, and Qiskit locally on your laptop or desktop.  The ``LocalPython.ipynb'' file provides
(an outline (of rudimentary)) instructions.


This repository is:

https://github.com/rpi-foci/IntroQuantumBeta.git


