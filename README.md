# challenge_18

## Project Overview
Build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.
---

## Technologies

The application is in python and is uing the following libraries:



* [pandas](https://pandas-profiling.github.io/pandas-profiling/docs/master/index.html) - For data analysis.

* [streamlit](https://github.com/streamlit/streamlit)- Used to build apps




# Imports


The operating system used in creating the application is Windows 10 64 bit. The application that used to code in notebook is VScode and then tested in Gitbash and Terminal. 

I created a engine for the application

The output file was read by:

```python
@dataclass
class Record:
    sender: str
    receiver: str
    amount: float
)
```
---

## Installation Guide

1. Open Gitbach or terminal and go ito the folder where you want to place the files.
2. Click on the blue "code" button which will allow you to clone.![<Code button in Github>]()
3. Then click on SSH or HTTPS as a clone method depending on if you have the SSH key setup. You will copy the link. You will then type "git clone" in Gitback or Terminal. Then paste the ssh or https information and press enter.
4. Next type "git pull" command in Temrinal or GitBash to pull the repository from the remote Github repository to a local directory on your computer.
5. You have access to the application. Also there will be all the python files that the application is depended on,  plus the excel file. 

---

## Usage

Below is a list of steps/analysis seen in the notebook:
    1.Create a new data class named Record. This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.
    2.Change the existing Block data class by replacing the generic data attribute with a record attribute that’s of type Record.
    3.Create additional user input areas in the Streamlit application. These input areas should collect the relevant information for each financial record that you’ll store in the PyChain ledger.
    4.Test your complete PyChain ledger.[<Screenshot>](images/screenshot.png)
    

---

## Contributors

This application was provided by the instrutor of Columbia University and addtional code was added by Khatija Azeem to complete the project.

---

## License

For this application, I used Github to uplaod the file into a repository. Since this is a public file, there will be no restriction on usage of this code. 
