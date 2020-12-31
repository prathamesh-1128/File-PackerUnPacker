# File-PackerUnPacker
In this Project we can merge multiple files into single file along with data.As well we can also extract all packed files whenever required.

Platform required:
        Windows NT platform OR Linux

Architectural requirement:
        Intel 32 bit processor

User Interface:
        Graphical User Interface  

Technology used:
        Java Programming
        
Features provided by File Packer-Unpacker:

This project is divided into two parts as Packing and Unpacking.

Packing Activity :
• In case of Packing activity we accept directory name and file name from user.
• We have to create new regular file as the name specified by the user.
• Now open the directory and traverse each file from that directory. In newly created file write Metadata as header and actual file data in sequence.
• Each name of file ,its size should be written in log file which gets created in system directory.
• After packing display packing report.


UnPacking Activity :
• In case of UnPacking activity we accept packed file name from user.
• Open the packed file in read mode and perform below activity as
• Read header
• From the name specified in header create new file.
• Write data into newly created file from packed file.
• Repeat all above steps till we reached at end of the file unpacked file.
• After unpacking display unpacking report.

Main purpose of this project is to merge large amount of files into one file by avoiding
memory wastage.
