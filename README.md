# install-Windows-10X-with-FFU
download source file from releases (https://tinyurl.com/y3lmbfxz) or download code;
and you'll see 10X.txt file. open txt and download.
Boot to Windows PE and flash with dism.(Guide : https://tinyurl.com/yyudjrze )
the dism command is "dism /apply-ffu /imagefile:Where Windows10X.FFU is located /applydrive:\\.\PhysicalDrive disknumber"
if it doesn't work, try "dism /apply-image /imagefile:Where Windows10X.FFU is located  /applydrive:\\.\PhysicalDrive disknumber"
