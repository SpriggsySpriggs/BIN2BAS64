# BIN2BAS64
This is a GUI adaptation of the code made by Dav for QB64 (http://www.qbasicnews.com/dav/files/basfile.bas) (originally in QBasic (http://www.qbasicnews.com/dav/files/bin2bas.bas)) that would turn any file into a .bas file that could then be included in QB64 code to be compiled and create the original file once again.

QB64, in which this program was written, can handle files up to 9 gigabytes. HOWEVER, this will not work for making a base64 binary file. Base64 makes files 30-33% larger, meaning that the memory for the program can easily be exceeded even with only an 8 megabyte starting file. I'm not sure what size file is the limit, but try sticking to icons, text files, small pictures, etc. This is not a viable option for making your own "zipped" installer or program as this makes all the files larger, actually.
