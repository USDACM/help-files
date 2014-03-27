help-files
==========

Installing Opera Browser
----------------
First, go to
 `https://github.com/USDACM/help-files` and click the "Download ZIP" button at the right-hand side

Now, open a terminal, `Applications->System Tools->Terminal` and type the following (you can copy and paste):

`cd Downloads;
unzip help-files-master.zip;
cd help-files-master;
./operainstall`

Now, when the configuration operations come up, just hit `Enter` for everything (don't actually type something unless you know what you're changing!)
Eventually it will all be finished and you can type

`./runopera.sh` and the opera browser will open!  Google Z-Type and you are good to go!  Good Luck!

The first file you should check out is "tutorials/github.txt".  There you will find the instructions on how to commit your changes from the Linux Lab to github.

This repository is intended to be a collection of help files for easy reference.  Basically, if you just spent 30 minutes figuring out how to set up Eclipse to work with github, or forgot for the millionth time how to compress/extract things from the command line, write/update a help-file!

Let's try to keep these to one file per useage.  That is, helpful "Vim" tricks go in "Vim.txt" and helpful Eclipse info go in "Eclipse.txt" etc.  If we find out that this configuration doesn't work, we'll come up with something that does.

Finally, help-files are meant to be short and quick little tidbits that are easy to read and implement.  If you want to describe something longer, then write a tutorial!  

Boiling it down, help-files contain many short tidbits about a single tool (like vim or eclipse or java etc.) while tutorials are of any length but deal with only a single issue (like how to install eclipse on your machine).


