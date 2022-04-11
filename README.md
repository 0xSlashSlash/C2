# Project Title

LQ

Within both the retail and commercial space, the abliity to save qualifying loans to a csv file is quite useful. This is a python script that assists in filtering and aggregating loans to accomplish such.

---

## Technologies

Python 3.9.7
    Imports
        sys
        fire
        questionary
        path
        time


---

## Installation Guide

1. Download all files from github repo.
2. Edit qualifier information as well as data utilized.
3. Run app.py and input commands as necessary.

---

## Usage

LQ is based around 4 core functions:

1. load_bank_data() will pull the relevant bank data available so as to have some metrics for loan availability.
2. get_applicant_info() then gathers an applicants information to reference it against the previously pulled bank data.
3. find_qualifying_loans() then filters the applicants data vs the bank data based upon previously determined filters and stores the filtered info.
4. save_qualifying_loans() finally gives the user a Y/N option to save the filtered information. 
    If Y is chosen, the user is asked to input a file path to where a csv copy of the filtered info will be saved upon which the program reads a closing message and then exits after 5s.
    If N is chosen, there is a closing message printed followed by the program exiting in 5s.

---

## Contributors

0xSlashSlash

---

## License

#Unsure of licenses.
