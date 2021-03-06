# Cantera Example guide and installation instructions
## Installation instructions
The following pieces of software will be installed 
 - Anaconda: a scientific and computing package for python that contains many popular packages and helpful tools
 - Cantera: a python package for combustion computation
 - Plotly: a graphing package for python
 - Tabulate: a python package for printing data nicely

It is anticipated that the following steps will take between 30 min and 1 hour depending on internet speed and familiarity with using the terminal. The download is ~450MB 
 
 ### Installation steps
 Note: All of the software in this tutorial is free. You do not need to purchase anything or enter any personal information to download and install this software.
  <ol>
   <li> From anaconda.org download the 64-bit version of anaconda for your operting system </li>
   <li> Install anaconda on your computer. The default settings in the installer are suggested and you do not need to install PyCharm </li>
   <li> Use the following steps to install the packages required </li>
   <ol>
   <li> Open the anaconda prompt (Linux and Linux users use the standard terminal) </li>
   <li> Copy and paste the following lines of code to install each package </li>
   
    conda install --channel cantera cantera
    
    conda install plotly
    
    conda install tabulate
   </ol>
  </ol>
  
 ### Download and open example code
 - Click on the green code button in the upper right hand side of the page
 - Download the zip file of the code
 - Extract the code to the folder of your choice
 - Open the anaconda prompt and navigate to the folder where the code was extracted
   - For windows: `cd` changes the path and `dir` lists what is in the current directory
       -  A tutorial is available here <https://www.computerhope.com/issues/chusedos.htm>
   - For mac and linux: `cd` changes the directory and `ls` lists what is in the current directory
       -  A tutorial is available here <https://help.ubuntu.com/community/UsingTheTerminal>
 - Once you have navigated to the directory enter the command `jupyter notebook` 
 - The landing page for jupyter notebooks should open as a new tab in your default browser
 - Open the `cantera_example.ipynb` file 
