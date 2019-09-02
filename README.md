# pselc : Select a PDF to open from your terminal
A bash script to display a menu showing all PDF files in a directory.

With the '-s' option, the script can also display PDF files in subdirectories of the main directory as well.
## Installation
1. Make the script executable : chmod +x pselc
2. Copy the script to your /usr/local/bin folder
## Usage
pselc \[options] \[directory]

options : &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-s  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Scan for PDFs in subdirectories as well
  
Warning: -s might be slow if you have hundreds of PDFs in a directory
