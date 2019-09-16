# CSB_Ex_1.10.4

### Extra Credit, worth 1 whole assignment (Due 09/20/2019):
Complete Exercise 1.10.4 Data Explorer (data from Buzzard *et al.*, 2016), and submit script by updating your repository (see below). You may work in groups but each student must submit their own work.

Hints:

* Start by cloning this repository to your computer (copy the link from the green button on the upper right, then goto your home dir in your terminal and type `git clone LINKTHATYOUCOPIED`)

* **_I highly recommend that you create your script in a text document in either Notepad++ or BBedit_**.  
* Make a copy of the `Buzzard2015_pseudo.md` document and a give it a new name as requested in the exercise or of your choosing.  It should end with an `.sh`
  * "Comment" the pseudo code using `#`
* Add a shebang!
* Use your terminal to play in this repository and construct/troubleshoot code
* Copy and paste working code into your script in your text editor
* I have noticed that the Win10-Ubuntu terminal does not like when you copy properly formatted code with leading tabs and spaces from your script in the text editor and paste it at the command line
  * You can, however, copy and paste the lines without the leading tabs and spaces
  * You can also create the script in the terminal using `nano` and paste in your properly formatted code to then run the script
    * Win10 only, it is critical that you do not modify files in your Ubuntu directory structure with Win10
	  * You can, however, move to your Win10 directory structure from the Win10-Ubunutu terminal and manipulate files as you wish `cd /mnt/c/Users/YOURUSERNAME`

### To `push` your changes to your repository on GitHub, and thus submit the assigment, do the following

* change directories to the directory for this assignment
* type the following:
```
git add *
git commit -m "updating my assignment"
git push origin master
```

Note that 
* you can change the `commit` message to whatever you want (the part in quotations, but keep it brief
* you will have to provide your github username and password for the `push` to `origin master`
