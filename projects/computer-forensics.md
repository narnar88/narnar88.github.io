---
layout: project
type: project
title: Computer Forensics
permalink: projects/computer-forensics
# All dates must be YYYY-MM-DD format!
date: 2017-03-15
labels:
  - Forensics
  - Data Recovery
summary: A mock computer forensics investigation done in a group in ICS 425. Areas of responsibility: Computer Forensics Lab, AccessData FTK Imager Tool, Recovering Deleted Files and Deleted Partitions, Forensics Investigation Using AccessData FTK, Forensics Investigation Using EnCase
---

Computer Forensics Investigation Process

For this lab the goal was to learn about the computer forensics investigation process. Aspects of the process include recovering deleted files from a hard drive, and then creating copies of these files. Also, how to use various programs to create hashes and checksums for files so that the values can be computed to the original values in order to verify that the files were not tampered with. In order to gain a better understanding of this process, along with the tools that can aid in this process, the lab was broken into three parts. The three parts were as follows:

1. Recovering Data Using the Recover My Files Tool

In order to recover lost data from a hard drive the lab utilized a tool called “Recover my Files”. This tool allows the user to search for deleted files on a hard drive. The user chooses the desired drive to look at (i.e. C: Drive or E: Drive, etc.). Once the drive is chosen, simply run the program and it will recover any deleted files. This tool allows the user to preview the files found, as well as sort the files by file type, it also allows the user to see when files were deleted. Unfortunately the user cannot choose to save the files found unless the full version of the program is purchased (the version used was a free version with limited access to the program’s capabilities). Regardless the free version can still be very useful since it allows the user to preview the deleted files, as well as see when the files were deleted.

2. Performing Hash, Checksum, or HMAC Calculations Using the HashCalc Tool

After recovering any lost data it is best to  make a copy of the original since an untampered copy will be needed if the user intends to manipulate the data. That being said, multiple untampered copies will be needed. In order ensure that two copies are the same, a hashing algorithm needs to be ran on the files. The algorithm generates a value for each file that can be compared against each other. In order to do this the lab used a tool called Hash Calc. Hash Calc allows the user to take a file and create a hash for it based on various hashing algorithms (SHA, SHA1, SHA256, SHA384, SHA512, MD4, MD5, etc.). It also allows the user to create a HMAC hash which is a “Hash Method Authentication Code” based on some text the user enters.

3. Generating MD5 Hashes Using MD5 Calculator

Lastly, the lab had me installed a program called MD5 calculator. This was a simple tool that when installed allows you to right click on a file and choose “MD5 Calculator”, which then will open the program and gives you the MD5 hash for that particular file. It also allows you to compare to MD5 hashes against one another to see if they’re equal or not.
 
Computer Forensics Lab

For this lab, the main purpose was to learn how to better perform basic computer forensics. The tasks included gathering evidence, viewing files that varied by format types, learning how to locate files, converting images and other data types, how to handle evidence, and how to create an image of a hard disk partition. In order to learn these skills, the lab was broken down into three parts, each of which introduced a new program in order to aid with these tasks. The three portions were as follows:

1. Gathering Evidence Using the Various Tools of DataLifter

The DataLifter tool had many different functions to try in the lab. The first one was the use of the “File Extractor” function which basically just extracts files from a location of the user’s choosing. For the purpose of this lab the “images” folder was extracted. The “Image Linker” function was the second function that the lab utilized. This allowed the user to choose a folder that contained images, then create an HTML file that contained all the said images for easy viewing. The lab also utilized the “Internet Cache and History Agent” function. This tool allows the user to choose data from a browser that has been saved as a “.dat” file, once a file is selected, the program will parse through the file and reveal the internet activity that took place based on that file. There were many other tools besides these that were also built into the program, such as a “File Signature Generator”, “Email Retriever”, and a “Final Report Generator”.

2. Viewing Files of Various Formats Using the File Viewer Tool

In order to learn how to view files of various types, this lab involved installing a program called “File Viewer”. The main purpose of File Viewer is to allow the user to locate and view files that vary by type. File viewer will show the file as well as allow the user to view the properties of that file. Lastly, it will allow the user to change the file extension for that particular file, if chosen to do so.

3. Creating a Disk Image File of a Hard Disk Partition Using the R-Drive Image Tool

The last step of this lab was to create a copy of a particular disk partition. In order to do this, a tool called, “R-Drive Image” was installed. This program allows the user to select a particular drive from the computer (for this lab the E: drive was chosen as the source, and the C: drive as the destination). This tool allows the user to create a password for the image, although this is not necessary for the operation to be completed. Once the operation starts, it takes roughly 20 minutes or so to complete (longer if the HD has more data). But once it’s done, the user has an image file that contains a copy of the entire hard drive.

Understanding Hard Disks and File Systems

The objective of this lab was to understand how to recover files deleted from a hard disk and analyze the file systems. 

Recovering Deleted Files from Hard Disks Using WinHex

   First the lab required installing and launching WinHex. To recover files in WinHex, the user must open an evidence file via WinHex and select “File Recovery by Type”, in this lab “.jpegs” was chosen as the type. A destination for the recovered files to be stored in must be selected. WinHex proceeds to automatically recover the files.
   
Analyzing File System Types Using the Sleuth Kit (TSK)

   First The Sleuth Kit (TSK) was launched. After viewing the system details, the program has the user view the details of the metadata structure. The Master File Table (MFT) has an entry for every file and directory (the layout is determined by pressing 0). Next the user views the MFTMirr file overview (entry 1) followed by viewing the boot file overview (entry 7). After, the user views the file volume overview (entry 3) then the AttrDef file overview (entry 4). Next, the user views the Bitmap file overview (entry 6), followed by the BadClus file overview (entry 8), then the secure file overview (entry 9). The user can then view a listing of all the files and directory names. Then by using the command “-d”, the program displays the deleted files. Also, by using “mg_stat”, the user can see the image file details.
   
Windows Forensics

   The objective of this lab was to find Windows event logs, Windows processes, search key values, and data in Windows, using Windows log analysis and file analysis forensic tools. 
   
Forensic Material on Computers Using OSForensics

   To start, the lab required the installation of OSForensics. After launching the program, a case was created using the wizard, then saved to the desktop. After searching for files and creating an index, the user can look through activity on the terminal and view the deleted files. FInally we looked through the system information. The next step was working with Hash Sets.  In order to investigate a suspect’s computer to locate evidence of a crime, a drive image was created and mounted to the newly created drive. After viewing the contents, a forensic copy of the Raw Image was created.
   
Extracting Information about Loaded Processes Using Process Explorer

   In this part of the lab, the main goal was learning how to investigate loaded processes by using the Process Explorer. 
   
Viewing, Monitoring, and Analyzing Events Using the Event Log Explorer Tool

   Here, the use learns how to view, monitor, and analyze various events. The program used for this was Event Log Explorer. It was a relatively straight forward program.
   
Performing a Computer Forensic Investigation Using the Helix Tool

   This portion focuses on using the Helix tool in order to assist with investigating computer-based crime. First, an image of the data being investigated was created. The tool then goes through the process of adding evidence files. Next, Nigilant32 was used from the incident response in Helix. The PC Inspector File Recovery program was then used in order to show deleted files. The program then explained how to look up files within the computer for the case, as well as the specific process of adding images.
   
Data Acquisition and Duplication

The goal for this lab was to introduce methods for acquiring hidden text strings and monitoring  system remotely. In this instance, investigation concerning NTFS streams from hard drives were analyzed. By investigating NTFS streams from hard drives, information concerning the files could be extracted. As previously mentioned, hidden text string files are as the name suggests, not obviously visible to the user.In this lab the methods are as follows:

Investigate NTFS File System using Disk Explorer

In order to browse an NTFS File system, one must use a program called Disk Explorer. Once installed, the Disk Explorer will be able to inspect various files for hidden content. In order to do so, the user must choose a file to open as a drive. Once opened this will provide the user two sections: the valid and invalid boot sector. These sectors will display the complete image file in full detail. The user has the option to switch between sectors by inputting their respective hex values. The user is also able to view each respective sector’s entire hex values. On top of that, the user can also choose to view the entire drive’s hex value. Disk Explorer is also able to export the results of the findings into a new file. Disk Explorer, however, is not the only unavailabe tool.

AccessData FTK Imager Tool

Another method of viewing hidden content is to utilize AccessData FTK Imager Tool. Once installed, the AccessData FTK Imager Tool will be able to inspect various files for hidden content. In order to do so, one must choose a file to open. Once opened, the AccessData FTK Imager Tool will provide access to said hidden content. This feature includes the ability to view the hex values of the files that were opened. 

Recovering Deleted Files and Deleted Partitions

The goal for this lab was to introduce methods for recovering deleted files as well as partitions. The extent of the ability to do so includes files deleted from the recycling bin. One is also able to recover files due to a hard disk crash or whether it has been reformatted or repartitioned. File recovery is even possible from USB drives and anything of that manner. These can be done through the following:

Recover deleted data using EASEUS Data Recovery Wizard

In order to recover deleted files, one could use the EASEUS Data Recovery Wizard. Once installed, the user will be able to recover data. This can be done by selecting the deleted file recovery option. Once chosen, proceed to choose the option of automatically recovering all lost files. From there the user must choose the partition from which the files were previously deleted. Doing so will result in recovering the files that were deleted. The tool also provides a feature to customize the area for which to save the previously deleted files from. 

Recover deleted data using Quick Recovery Tool

Another method of recovering deleted files is to use Quick Recovery Tool. As such, Once downloaded and installed, the user will be prompted to choose the disk from which the files were deleted from. Following this, the user will now need to choose the partition so as to search for the deleted files. The files will now have been recovered upon completion of the search. 

Forensics Investigation Using AccessData FTK

The program AccessData FTK allows users create and view cases. When working on a case AccessData FTK allows users to add, delete, edit, and refine evidence. The type of evidence that can be used includes acquired images of drives, local drives, folder contents and individual files. In this module, a new case was created using an “Acquired Image of Drive”. When adding evidence, each addition gets an “Evidence Identification Name/Number”. There are also various options such as recalculating hash values, carve files, etc. The program then automatically processes the evidence file(s). While doing so the program gives details on the process such as the path of the evidence item being processed, the current item type, size, and the progress of the item within the evidence that is being processed. There is a separate window that shows how many evidence items there are, total file items, encrypted files, deleted files, email files, spreadsheets, graphics, multimedia items, email messages, etc. In this case, there is 1 evidence item, 1990 total file items, 445 deleted files, 103 multimedia files, and 1066 graphic files. There are also tabs specifically for graphics, email, searching, bookmarks, etc. The graphics tab gives a tree of folders, folders containing images, if clicked on, show a grid view of the graphics in the selected folder. Evidence can also be searched, if searched, search results can also be filtered. After all evidence is processed, the program generates a report, case log, and evidence list. These 3 combined give a detailed review of the investigation.

   Based on the evidence examined, there is no trace of cybercrime. Contents of the files processed contained no incriminating evidence. The contents of the examined files were primarily generic, non-incriminating graphics. The contents of the remaining portion of evidence, such as multimedia, were also not incriminating as they contained nondescript folders and files.
 
Forensics Investigation Using EnCase

EnCase allows users to process data, then search, bookmark, and view evidence. In this investigation, a partition of a computer was examined as evidence. EnCase has a similar process and capabilities as AccessData FTK, such that the program generates a report of the evidence and users can view evidence in Hexadecimal, and export files. The program also allows users to have a “Disk View” of the evidence. There is also a tab labeled “Timeline” that allows user to see all times that the selected file was created, written, accessed, modified, deleted, and acquired. The only downfall of the program is the extensive amount of time required to conduct a search on the evidence. 

   In this investigation, after processing the partition as evidence, the files were searched. The search results, or Search Hits in EnCase, returned a tree of folders containing various types of evidence files. The folder with the most concern was the email folder, as this is a common method of communication. The email folder contained a subfolder of deleted emails. One of the deleted emails with the subject, “Re: I like the deepthroat pic” contained a message in the body revealing the suspect’s plans on planting Trojans, what programming languages they planned to learn in order to create said Trojans, and so forth. Based on the contents of the deleted emails, David had committed fraudulent trading. He may also be considered  and investigated for other illegal acts based on the substantial amount of incriminating evidence in his emails.
