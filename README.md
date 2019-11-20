# t2k_ctags
The ctags config files for T2000 test platform

# how to use it with ctags
put the t2k.ctags file under the C:\Users\user_name\ctags.d folder, and enjoy it with ctags

# how to use it with ctags + Notepad++
1. put the t2k.ctags file under the %systemdrive%%homepath%\ctags.d
2. install NppTags for Notepad++, restart Notepad++
https://www.fesevur.com/npptags/
3. enjoy it

Note:
1. please note the timing of tags.sqlite file generatting. 
   if you start the npp first time, click generate, then tags.sqlite file will generate into current focus file's folder
   if you already click generate after npp start, and click second times, the tags.sqlite file location will remember
   if you need create a new tags.sqlite file for difference fodler, please restart npp

2. if the tags.sqlite folder is not what you want, you can move it manually and regenerate

3. only support 32bit version npp

# last
if the previous method is not work, please try below:
1. download npp_ctags_t2k.zip, unzip it
2. put the ctags.d folder into %systemdrive%%homepath%\ctags.d
3. put the NppTags folder into Notepad++'s plugins folder, restart Notepad++
4. enjoy it
