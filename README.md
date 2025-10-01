<!-- [<img src="https://qbraid-static.s3.amazonaws.com/logos/Launch_on_qBraid_white.png" width="150">](https://account.qbraid.com?gitHubUrl=https://github.com/rpi-foci/IntroQuantumBeta.git) -->

[![Env Badge](https://img.shields.io/endpoint?url=https://api.qbraid.com/api/environments/valid?envSlug=rpi_qu_8b7d9z&label=Launch+on+qBraid&labelColor=lightgrey&logo=rocket&logoSize=auto&style=for-the-badge)](http://account.qbraid.com?gitHubUrl=https://github.com/rpi-foci/IntroQuantumBeta.git&envId=rpi_qu_8b7d9z)


# Introduction to Quantum Computing Workshop

This is the Beta version of a Workshop to step participants through
running their first program on a quantum computer.  In this workshop,
we will:

   * Request access to RPI's Quantum System One (if needed), and create an IBM Quantum Cloud account
   * Create a gBraid account (if needed)
   * Open qBraid from this GitHub repository
   * Launch Jupyter Labs, and install the course's kernel
   * Load the runtime Jupyter lab, and configure the Qiskit Runtime
   * Load HelloBell Jupyter lab and run a simple measurement of a Bell state
   * Run the same program, but with unentangled qubits
   * Discuss and compare results
   * Optionally install miniconda and Qiskit locally

For those interested, and time permitting, instructions for a local installation
of Python (miniconda), and Qiskit are provided.

## Request an IBM Quantum Cloud (quantum computer) account

If you do not already have a quantum computer account,
[request one](https://webforms.rpi.edu/form/rpi-quantum-hub-access-request)

Accept the invitation link, and create your IBM Quantum Cloud Account.  Information needed
for the Qiskit Runtime is found there.

## Create a qBraid account, and logon to qBraid

Before launching qBraid, create a qBraid account at [https://www.qbraid.com](https://www.qbraid.com).  This can
be created using your RPI email address, or another address.  If you already have a qBraid account login.

## Launch qBraid

Click the "LAUNCH ON QBRAID|RPI QUANTUM COMPUTER WORKSHOP" button.

This will launch qBraid.  *Note, you may want to launch in a separate tab or window to keep these instructions.*

qBraid will take a few moments cloning the git repository and setting up your workspace.

## Launch Jupyter Lab and Install the Course's kernel

Under Launch Lab, select the "Default Workspace", and click "Next".

Select "Free 2vCPU 4GB Ram".  You may have to start the
lab, or it may already be running.  Click the "Launch Lab" button.

Once the lab is launched, EWS tab on the upper right corner.  This will show the Default kernel,
and the "RPI Quantum Computing Workshop" kernel.

Click the drop down for the RPI kernel, and add it.  This will load the required Python packages,
including Qiskit.

Note the "+ ADD" link at the top can be used to add more environments, such as PennyLane.

## Open Class Lab Folder

On the left side of Jupyter Lab there should be a "IntroQuantumBeta" folder. Double-click it.

## Configure Qiskit Runtime

Double-click "Runtime.ipynb" on the left.  This will open the Jupyter lab.

On the top right of the lab is the current Python kernel.  Make sure
it is: "Python 3 [rpi-quantum-comp]" If not, click and select the
kernel course's kernel.

Follow the lab for instructions on configuring the Qiskit runtime.

## Run the HellBell program

After the runtime is configured, click on "HelloBell.ipynb".  Ensure the "rpi-quantum-comp" kernel is
being used.

Follow the instructions in the lab to run (your first?) quantum computer program on RPI's Quantum System One.

## Install Python and Qiskit Locally

qBraid hosts a Jupyter Hub, a Jupyter Lab for running Python programs.  But you can install Python,
Jupyter Lab, and Qiskit locally on your laptop or desktop.  The "LocalPython.ipnb" file provides
(an outline) of instructions.


This repository is:

https://github.com/rpi-foci/IntroQuantumBeta.git


