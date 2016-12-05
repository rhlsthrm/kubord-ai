# kubord-ai

Simple example program to demonstrate a basic predictive engine.

# Prerequsities
* **Node.js** (tested with v5.11.0 only, should work with other versions)
    * Install using instructions at https://nodejs.org/en/download/.
* **prompt** npm package (https://github.com/flatiron/prompt)
    * Command line install (requires Node): 

    `$ npm install prompt`
    
# Usage
* Unzip files.
* Navigate to files in terminal window.
* Use the following command to run the program:
   
   `$ node kubord.js`
* Follow prompts on the command line, and use "x" to quit (ctrl-C/cmd-C force quits).

# Possible Improvements
* Store data in database to persist trends across sessions. Right now, data is stored in memory and a new session will reinitialize all user input data.
* Use cloud database to build big data engine. This engine will store data from all users and can be used to find patterns within the data, such as "users who choose "Y" 7 times in the last 10 choices choose "Y" again on the 11th time 65% of the time" to make more educated guesses.
