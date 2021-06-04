---
layout: default
title: 
permalink:
---

<h1> Homework 2</h1>

video 
You've been given a collection of digitized images, but before they go into the repository, you must complete additional actions as part of you digital workflow. You will be using ReNamer, TSR Watermark Software or iWatermark, and ExifTool to update and manage a small collection of images. These images were scanned by different people for different purposes. The file names are not normalized. [Get your assigned photos and college here.](http://www.greengrove.markdwolfe.com/ist653/)

# Part 1 (5 points) Getting Your File Names Ready

- **Using Renamer:**

	- look up OCLC code for your assigned college or university, and append to file name: [OCLC Codes for libraries](http://www.oclc.org/contacts/libraries.en.html)
	- change case of file extension from upper to lowercase
	- serialize your file names, add leading zeros for 6 charcter serial
	- make lowercase and remove unconvetional characters or spacings
	- append Exif Date, just the year <span style="font-family:Courier">(YYYY)</span> to the file name by clicking on <span style="font-family:Courier">Insert Meta Tag</span>.
	- format your file name so it goes from general to particular, left to right.


- **Update Embedded Metadata using Exiftool and MS Excel:**

	- using Exiftool, update all of the city and copyright tags with your college's hometown and name respectively. See IPTC's city tag name [[here]](https://exiftool.org/TagNames/IPTC.html) and EXIF's copyright tag name [[here]](https://exiftool.org/TagNames/EXIF.html).
	- export a .csv/Excel file, the following tags: filesize, filetype, copyright, city, and createdate
	- in Excel, truncate your CreateDate column to year only, using a formula something like this: <span style="font-family:Courier">=LEFT(A1,LEN(A1)-3)</span>
	- create a <span style="font-family:Courier">Sum</span> for your total file size.
the .csv file should look something like this, but with updated file names: [.csv]

# Part 2 (5 points) Getting your Images Ready

- **Using PhotoScape**
	- create watermark by choosing icon from assigned college make watermark transparent and defined, save as .jpg
		- [Video tutorial](https://www.youtube.com/watch?v=ei0UoIIU_Yo&t=196s) using PhotoScape 
	- reduce images in size using Resize Images section on the last tab, files should be about 100k per file
		- [Video tutorial]() resize images using PhotoScape 


<br/>

- **Due .** 

- Assignment is worth 10 points. 

- **Email me one .zip file** that includes: completed .csv file, folder of reduced and watermarked files, and a copy of your DOS comands in a .txt file. You can retype them or copy them from the DOS terminal. Work in groups or by yourself, if you like. Please post all questions, comments, and help in the Homework 2 discussion forum. 