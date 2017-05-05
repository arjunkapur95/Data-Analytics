Readme

- In order to run the code you will need to have python, pysprak and jupyter (or any ide capable of running .ipynb) installed on your machine. 

To run the code simple:

    - upload the file to jupyter
    - ensure that assignment2LoadData is in same directory as the code

Then simply run the code from top to bottom on jupyter.


Key areas:
    - to change the sample size change the value of n in Decrease or increase sample size section - cell 3.

    - variable c in Min Hashing section needs to be smallest prime number greater than number of OHE features. 
      this link should be helpful - http://www.numberempire.com/primenumbers.php

    - to change the number of hashes, you can simply change the variable numHashes in Min Hashing section- cell 6. 

    - to change the number of hashes that need to match in order to classify things into same bucket - change the value in line 23 of Classification section - cell 8. 
    - to change the number of neighbours in KNN classification change the variable k in line 6 in KNN section - cell 12. 

Known issues

    - memory error at high sample size
        - possible fix - upgrade memory 


Testing machine specs:

    - processor: i5 4300U @ 1.90 ghz
    - memory: 4gb ddr3 1600mhz