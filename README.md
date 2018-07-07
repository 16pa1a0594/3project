# Project 3: Logs Analysis Project

Logs Analysis Project, part of the Udacity [Full Stack Web Developer
Nanodegree]
(https://www.udacity.com/course/full-stack-web-developer-nanodegree--nd004).


## What it is and does

A Reporting page that prints out reports in a plain text format based 
		on the data in the database.This reporting tool is a python program using the `psycopg2` module to connect to the database.


## Required

Python
Vagrant
VirtualBox


## Project contents

This project consists for the following files:

* newsdata.py - main file 
	to run this Logs Analysis Reporting tool
* README.md - instructions to install this reporting tool
* output.txt - output file that
 	will shown on the command prompt

## How to Run Project

Download the project zip file to you computer and unzip the file.

  
	1. Launch the Vagrant VM inside Vagrant sub-directory in the downloaded fullstack-nanodegree-vm repository using command:
  

 		 ```
    $ vagrant up
  ```
 
	 2. Then Log into this using command:
  
  ```
    $ vagrant ssh
  ```
  
3. Change directory to /vagrant and look around with ls.
  ```
    $ python newsdata.py
  ```



## Miscellaneous

This README
 document is based on a template suggested by PhilipCoach in this
Udacity forum [post](https://discussions.udacity.com/t/readme-files-in-project-1/23524).
