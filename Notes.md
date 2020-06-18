# Week 6 Notes

Got a list of urls from the [Boys Will Be Boys Collection in the Digital Transgender Archive](https://www.digitaltransgenderarchive.net/catalog?f%5Bcollection_name_ssim%5D%5B%5D=Boys+Will+Be+Boys+), made a urls.text of them, used wget to download them all responsibly. Then since they just saved as plain files, I looked up how to mass convert file names to pdf using the command prompt from [this](https://youtu.be/TjdTFQKQykg?t=103) video which turned them into legible pdfs.


Then I had to convert them from pdf files to txt files. I wanted to automate it and do it using R or Python, however I ran into the issue that these are newspaper articles that have multipe columns meaning that R reads everything top to bottom, left to right which means it completely jarbled the text as seen [here](PDFtoPNGtoText.png). So after troubleshooting that to see if there were any other methods out there, I tried the tried-and-true method of copy/pasting the text from the pdfs into sublime text and then saving them as text files.
This saved the columns, but since they were scanned with multiple pages per pdf page, some things are out of order. Better than all of the text being jumbled though.


## Voyant
Imported all the documents into Voyant to experiment with. 
Played around with a few of the tools.


## AntConc
Imported all the documents into AntConc for analysis. Experimented with the various search filters.

