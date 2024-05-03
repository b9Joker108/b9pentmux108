[![Python](https://img.shields.io/badge/language-Python%203-blue.svg)](https://www.python.org)
[![Bash](https://img.shields.io/badge/language-Bash-blue.svg)](https://www.gnu.org/software/bash/)

# b9pentmux108 (under construction)
`b9pentmux108` is a tool that helps you install and use multiple penetration testing and hacking tools on Android systems with ease. It allows users to easily install and use a variety of popular tools such as Nmap, SQLMap, and Metasploit, for example. The tool is simple to use, as you only need to type a command to install and use any of the tools. `b9pentmux108` is an open-source project and may be a very helpful tool for penetration testing and ethical hacking tasks.

Made with ❤️

## Database
Since forking this repository, I have been actively acquiring Python to realise a knowledge graph for 
another project. Thatbhas been progressing, but is a mighty task with many moving parts, and individual 
learning learning requirements. Upon first forking this repository, and git cloning it locally, I have
been actively interrogating the codebase and reverse-engineering its workings, to understand how it
effectively works together. Further to this, the first real initiative was to excavate the .db file, 
and determine how best to work with it. I learnt that the .db file was actually interrogable in Termux
with the commandline tool `sqlite3`, the package of which is in the official Termux repository. I then
came to appreciate, that SQLite is very popular in coding globally. I found using `sqlite3` to 
interrogate and query the database, clunky and not really suitable for my purposes. I really wanted to 
visualise the database and its elements, and I couldn't find a way to do that in the .db format in 
Termux, or through an Android app. I learnt that visualising and editing a .db file within Termux on
an unrooted device is not feasible. Since then, I have written Python scripts to convert the .db to 
.xml, .json and .csv. All these data formats, namely: XML, JSON and CSV, I had become aware of, in 
researching my other Python project, to realise a knowledge graph. I have since determined, that for 
this project, the most appropriate data structure instead of .db, would actually be a Python module,
of nested dictionaries,which I am yet to produce. From there, the logic of the codebase needsmust be
refactored to reflect this design choice. That is yet to be done. My Python skills are not yet 
foundational enough, to reactor this codebase, in light of this transition from .db to a module of
Python nested dictionaries. But, I will keep at it.


## Feature
- **Tool Installation**  
Install Single Tool  
`lzmx > set_install 1`  
Install Multi Tool  
`lzmx > set_install 1 2 3 4`  
Install All Tool  
`lzmx > set_install @`  
- **Default Dir Install**
On `lazymux.conf` replace symbol ~ with directory you want  
Example: lazymux.conf  
`HOME = /sdcard`


## Screenshot
TBA

### Requirements
• Python 3.x

#### Installation and Using Lazymux
```bash
apt install python git
git clone https://github.com/Gameye98/Lazymux
cd Lazymux
python lazymux.py
```
