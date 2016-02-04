# datacomdownloader

To run this program, go to the directory of this program by terminal, then:

./srget -o [saved_file_name] -c [numConn] [Address]

where saved_file_name is your desired file's name to download and address including http.
-c indicates multiple connection mode. numConn is the number of connection, 5 if not provided

----------------------------------------------------------------------------------------------------

This program works with http only.

----------------------------------------------------------------------------------------------------

If the file's name already exist in your directory, "File already existed" will be printed
on your screen.

----------------------------------------------------------------------------------------------------

If the download is not finished/got canceled, it will save as <saved_file_name>.dwnld and extra file
<saved_file_name>.dwnld.head and <saved_file_name>.pickle
    
    * If you want to resume the download in the future, please DO NOT DELETE those two files

----------------------------------------------------------------------------------------------------

If the file has been damgaged, inluding the extra files indicating above, it will print out on screen
and restart the download

----------------------------------------------------------------------------------------------------

Single connection is recommended as it will be faster

----------------------------------------------------------------------------------------------------

To resume the download, run the program similar to the first time you run it

----------------------------------------------------------------------------------------------------

This program does not support chunk-encoding transfer

----------------------------------------------------------------------------------------------------

If the file has been updated, it will be printed out on screen

----------------------------------------------------------------------------------------------------

