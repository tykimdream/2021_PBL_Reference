# Malware-Detection-using-Machine-Learning
Malware detection on Android devices using machine learning classification methods.
This repository is a proof of concept for malware detection on Android devices using behavioral features. 


## Data
Current data includes 100.000 samples apk samples.
Previous data is extracted from the proc virtual file system. data.csv file contains the process samples from Ubuntu Desktop environment.

## Features (For each apk) - will be uptaded soon
* RUSER: Real user id. Textual or decimal representation.
* PPID:  Select parent process by process id.
* UID: User id number
* PID: User id
* PGRP: Process group id
* %CPU: CPU utilization of the process in ##.# format
* %MEM: Memory usage of the process
* VSZ: Total virtual memory size in bytes
* TIME: Total accumulated CPU utilization time for the process
* SIZE: Memory size in kilobytes
* legitimate: Labeled as 1 if the process is legit. Labeled as 0 if the process is malware.

## TO-DO List
* data.csv file will be updated with real malware samples. (Done)
* Data extraction script will be pushed to the repository
* Feature selection algorithms will be applied for better results.
* More relevant features may be extracted from the kernel.
* A script will be written to do the whole process in real time at the user space.
* A kernel driver will be written to do the whole process in real time at the kernel level.
