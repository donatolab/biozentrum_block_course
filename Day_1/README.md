# Day tasks

## Python tasks

1. Start anaconda envrioment. In windows start the command terminal for anaconda by typing in "anaconda" in the windows task bar and clicking on "command prompt".


2. Clone the biozentrum blockcourse from github from the anaconda command prompt.

`git clone https://github.com/donatolab/biozentrum_block_course`


3.  Load jupyter lab from the anaconda command prompt.

`jupyter lab`


4. Try to run the first cell of the jupyter - you should get an error


5. Install missing packages using pip. We type in "pip install PACKAGE" and the pip package manager finds the package for us and installs it.

`!pip install matplotlib`
`!pip install scipy`
`!pip install tqdm`
`!pip install sklearn`
`!pip install parmap`
`!pip install networkx`
`!pip install pandas`


6. Re-Run the first cell in the notebook. You should not get any errors now.


7. Ok, good so far!   Next we get the data that we require for the analysis. 


8. We start by runnign the jupyter notebook cell that links to our google data drive. Once there we right click on the file to download it.  Make sure you remember the location of where the file is downloaded.


9. Next we unzip the file by using the Windows folder navigator, clikcing on the file and unzipping it to a specific location (we can use the current location if that's easiest).


10. We then proceed to make load our Calcium processing pipeline by making a calcium object 'c'.


11. We then load the suite2p data that we downloaded.  You should now see some information about the downalod datasets.  
For example, the array self.F has two entries (1232, 55740).  What do the 2 values represent? 
