# Day tasks

## Python tasks

1. Start anaconda envrioment. In windows start the command terminal for anaconda by typing in "anaconda" in the windows task bar and clicking on "command prompt".


2.  First thing, we need to activate our anaconda environment that we want to work in.  

`conda activate suite2p`



3. Next, we need to get the biozentrum blockcourse from github.  So we use the "git" function from the anaconda command prompt to "clone" (i.e. copy) the course locally:

`git clone https://github.com/donatolab/biozentrum_block_course`



4. We are now ready to open the jupyter lab notebook from the anaconda command prompt.

`jupyter-lab`


5. Now we have to find the notebook (or code) that we want to run. So we click on the "notebooks/" folder and then on the Binarize_Suite2p notebook.


6. Next, we are ready to try and run our first cell of code.  We click on the top most "cell" and then in the "run" (triangle) button at top of the notebook. 

... but, we get our first crash :/ 

                  Congratulations! 

... and don't worry, crashes are part of coding life :)


7.  Python is telling us that it does not know the name of some of our requested packages. This usually means we forgot to install them. So, we now
install the missing packages using the `pip` package manager. 


8.  So, we type in "pip install PACKAGE" in a jupyter lab cell for every missing package and the pip package manager 
will find the package on the internet for us and install it... 

`!pip install matplotlib`
`!pip install scipy`
`!pip install tqdm`
`!pip install sklearn`
`!pip install parmap`
`!pip install networkx`
`!pip install pandas`


9. Re-Run the first cell in the notebook. You should not get any errors now. Yey!!!


10. Ok, good so far!   Next we get the data that we require for the analysis. 


11. We start by running the jupyter notebook cell that links to our google data drive. Once there we right click on the file to download it.  
Make sure you remember the location of where the file is downloaded.


12. Next we unzip the file by using the Windows folder navigator, clicking on the file and unzipping it 
to a specific location (we can use the current location if that's easiest).


13. We then proceed to make load our Calcium processing pipeline by making a calcium object 'c'.


14. We then load the suite2p data that we downloaded.  You should now see some information about the downalod datasets.  
For example, the array self.F has two entries (1232, 55740).  

`Pop quiz: what do the 2 values represent?`


15. For the next steps follow the instructions in the jupyter lab notebook...


... good luck!
