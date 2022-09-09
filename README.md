# CSB_Ex_1.10.4

### Extra Credit, worth 1 whole assignment:

Complete Exercise 1.10.4 Data Explorer (data from Buzzard *et al.*, 2016), and submit script by updating your repository (see below). You may work in groups but each student must submit their own work.

---

#### Exercise 1.10.4 Data Explorer

Buzzard et al. (2016) collected data on the growth of a forest in Costa Rica. In the file `Buzzard2015_data.csv`, you will find a subset of their data, including taxonomic information, abundance, and biomass of trees.

Write a script named `explore.sh` that, for a given CSV file and column number, prints
	● the corresponding column name;
	● the number of distinct values in the column;
	● the minimum value;
	● the maximum value.

For example, running the script with

```bash
$ bash explore.sh ../data/Buzzard2015_data.csv 7
```

should return

```
Column name:
biomass
Number of distinct values:
285
Minimum value:
1.048466198
Maximum value:
14897.29471
```

Note that in the example above, the script `explore.sh` accepts two arguments: the name of the file and the index number of the column

---

Hints:

* Start by cloning this repository to your computer 
  * copy the link from the green button on the upper right of this webpage
  * goto your home dir in your terminal and type `git clone LINKTHATYOUCOPIED`)
    * replace LINKTHATYOUCOPIED with the link that you copied from the green button
You are asked to create a script that accepts a file name (in this case `Buzzard2015_data.csv`) and prints information about the file to the screen.  Please read the question in the book.

```bash
# script should be run as follows
$ bash explore.sh ../data/Buzzard2015_data.csv 7
```

```bash
# script output should look like this:
Column name:
biomass
Number of distinct values:
285
Minimum value:
1.048466198
Maximum value:
14897.29471
```

* **_I highly recommend that you create your script in a text document in either Notepad++ or BBedit_**.  
* Make a copy of the `Buzzard2015_pseudo.md` document and rename it `explore.sh`.  
  * "Comment" the pseudo code using `#`
* Add a shebang!
* Use your terminal to construct/troubleshoot code
* Copy and paste working code into your script in your text editor
* I have noticed that the Win10-Ubuntu terminal does not like when you copy properly formatted code with leading tabs and spaces from your script in the text editor and paste it at the command line
  * You can, however, copy and paste the lines without the leading tabs and spaces
  * You can also create the script in the terminal using `nano` and paste in your properly formatted code to then run the script
    * Win10 only, it is critical that you do not modify files in your Ubuntu directory structure with Win10
	  * You can, however, move to your Win10 directory structure from the Win10-Ubunutu terminal and manipulate files as you wish `cd /mnt/c/Users/YOURUSERNAME`, where YOURUSERNAME is your user name on win 10, which can be different than your user name in Ubuntu.

---

### To `push` your changes to your repository on GitHub, and thus submit the assigment, do the following

* change directories to the repository directory for this assignment
* type the following:
```
git add *
git commit -m "updating my assignment"
git push origin master
```

this can be done repeatedly.

Note that 
* you can change the `commit` message to whatever you want (the part in quotations, but keep it brief
* you will have to provide your github username and password for the `push` to `origin master`
