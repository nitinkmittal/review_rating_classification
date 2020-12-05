# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact

### Installing tensorflow-gpu ###
* Local Machine Specifications : Nvidia GT 940M 2 GB
1. NVIDIA® GPU drivers - latest
2. CUDA® Toolkit — CUDA® 10.2, provides .exe, easy installation, link : https://developer.nvidia.com/cuda-10.2-download-archive?target_os=Windows&target_arch=x86_64&target_version=10&target_type=exenetwork
3. cuDNN SDK 7.6.5 for CUDA 10.2, zipped folder, unpack, no installation, link : https://developer.nvidia.com/compute/machine-learning/cudnn/secure/7.6.5.32/Production/10.2_20191118/cudnn-10.2-windows10-x64-v7.6.5.32.zip
4. Move bin, lib, include from cuDNN SDK 7.6.5 to respective folders files in CUDA 10.2 
5. Download cudart64_101.dll using link : https://www.dll-files.com/download/1d7955354884a9058e89bb8ea34415c9/cudart64_101.dll.html?c=N0hhZkExU1FieGZlbktKRC9XQU80UT09 and move .dll file into bin folder of CUDA
6. Setup environment path for CUDA bin and libnvvp
7. Install tensorflow using : conda install tensorflow-gpu