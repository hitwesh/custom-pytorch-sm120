ML Workspace
=============

Overview
--------
This workspace contains a prebuilt Windows wheel for PyTorch.
It is built for sm_120 architecture, specifically for RTX 5060 Ti 16GB.

Contents
--------
- wheels/torch-2.12.0a0+gitd62bd2b-cp311-cp311-win_amd64.whl

Requirements
------------
- Windows 64-bit
- Python 3.11
- pip

Steps to download
--------
Go to Release - Version-1 and download the .whl file

Install
-------
From this workspace root:

	python -m pip install --upgrade pip
	python -m pip install wheels/torch-2.12.0a0+gitd62bd2b-cp311-cp311-win_amd64.whl

Verify
------
Run a quick import check:

	python -c "import torch; print(torch.__version__)"

Notes
-----
- This is a nightly build (git-based version string).
- If you use a virtual environment, activate it before installing.
