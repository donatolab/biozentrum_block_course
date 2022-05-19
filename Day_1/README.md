# Day tasks

## Python tasks

1. Start anaconda envrioment. In windows start the command terminal for anaconda by typing in "anaconda" in the windows task bar and clicking on "command prompt".


2. Clone the biozentrum blockcourse from github from the anaconda command prompt.

`git clone https://github.com/donatolab/biozentrum_block_course`


3.  Load jupyter lab from the anaconda command prompt.

`jupyter lab`


4. Now we have to find the notebook (or code) that we want to run. So we click on the "notebooks/" folder and then on the Binarize_Suite2p notebook.


5. Next, we are ready to try and run our first cell of code.  We click on the top most "cell" and then in the "run" (triangle) button at top of the notebook. 

... but, we get our first crash :/ 

                  Congratulations! 

... and don't worry, crashes are part of coding life :)


6.  Python is telling us that it does not know the name of some of our requested packages. This usually means we forgot to install them. So, we now
install the missing packages using the `pip` package manager. We type in "pip install PACKAGE" and the pip package manager finds the package for us and installs it.

`!pip install matplotlib`
`!pip install scipy`
`!pip install tqdm`
`!pip install sklearn`
`!pip install parmap`
`!pip install networkx`
`!pip install pandas`


7. Re-Run the first cell in the notebook. You should not get any errors now.


8. Ok, good so far!   Next we get the data that we require for the analysis. 


9. We start by runnign the jupyter notebook cell that links to our google data drive. Once there we right click on the file to download it.  Make sure you remember the location of where the file is downloaded.


10. Next we unzip the file by using the Windows folder navigator, clikcing on the file and unzipping it to a specific location (we can use the current location if that's easiest).


11. We then proceed to make load our Calcium processing pipeline by making a calcium object 'c'.


12. We then load the suite2p data that we downloaded.  You should now see some information about the downalod datasets.  
For example, the array self.F has two entries (1232, 55740).  
- What do the 2 values represent? 


13. For the next steps follow the instructions in the jupyter lab notebook...


... good luck!
