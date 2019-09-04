# OpenRefine Tutorial

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>
DataBasic tutorial by <a href="dlac.grinnell.edu" rel="cc:attributionURL">Katherine Walden, Digital Liberal Arts Specialist (Grinnell College)</a> is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

# What is OpenRefine?

According to [OpenRefine.org](http://openrefine.org/), “OpenRefine (formerly Google Refine) is a powerful tool for working with messy data: cleaning it; transforming it from one format into another; and extending it with web services and external data.”

## Data

Download the CSV files in the “Lyrics” folder and save to your Desktop.

These files include plain-text lyrics of the songs on Daddy Yankee’s Barrio Fino album. These lyrics were gathered using the [Genius Lyrics Tidy Data Extractor](https://dasil-jarren.shinyapps.io/genius-app/) Shiny app created by [Jarren Santos.](https://github.com/jarrenls)

Open one of these CSV files in a spreadsheet program like Microsoft Excel to see how the lyric data is structured. 

## Launching OpenRefine

OpenRefine is already installed on the lab computers. [Click here](http://openrefine.org/) to download and install it on your own computer.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_1.jpg?raw=true" alt="Capture" /></p>

Search for OpenRefine on your computer, and open the folder that appears in your search results.

Double click on the Application item to launch the program.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_2.jpg?raw=true" alt="Capture" /></p>

OpenRefine will initially launch via a terminal window. This window will need to remain open while you are using the program.

<blockquote>What is the command line?

Most of the time, we interact with digital technology via graphical user interfaces (GUI). The Command Line Interface (CLI) is an alternate way of working with a computer to navigate folder structures, create and edit files, and launch software programs.</blockquote>

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_3.jpg?raw=true" alt="Capture" /></p>

Once launched, OpenRefine will open a new browser window.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_3a.jpg?raw=true" alt="Capture" /></p>

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_3b.jpg?raw=true" alt="Capture" /></p>

OpenRefine’s default language is English, but you can choose from a range of language options that include English, Chinese, Spanish, French, Russian, Portuguese (Brazil), German, Japanese, Italian, Hungarian, Hebrew, Filipino, Cebuano, and Tagalog.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_5.jpg?raw=true" alt="Capture" /></p>


<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_4.jpg?raw=true" alt="Capture" /></p>

Click Browse and select the CSV files you saved to your Desktop. 

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_5.jpg?raw=true" alt="Capture" /></p>

Click the Next button.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_6.jpg?raw=true" alt="Capture" /></p>

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_7.jpg?raw=true" alt="Capture" /></p>

Click Select All to import all the individual CSV files into a shared OpenRefine work space. Combining these files is possible because they all use the same data structure.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_8.jpg?raw=true" alt="Capture" /></p>

Click the Configure Parsing Options button.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_9.jpg?raw=true" alt="Capture" /></p>

Our last step before working with the data in OpenRefine is to select a character encoding option. Click on the text box next to “Character encoding” to choose from a pop-up window of options.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_10.jpg?raw=true" alt="Capture" /></p>

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_11.jpg?raw=true" alt="Capture" /></p>

Select UTF-8 from the list of options. [Click here](https://www.w3schools.com/charsets/ref_html_utf8.asp) to learn more about UTF-8 character encoding.

<blockquote>What is Character Encoding? 

According to the [World Wide Web Consortium (W3C)](https://www.w3.org/International/questions/qa-what-is-encoding), “all characters are stored in computers using a special code, like the ciphers used in espionage. A character encoding provides a key to unlock (ie. crack) the code. It is a set of mappings between the bytes in the computer and the characters in the character set. Without the key, the data looks like garbage.” Character encoding is especially significant when moving data across platforms (Google Sheets to Microsoft Excel to OpenRefine, etc.) and when working with languages that have special characters. </blockquote>

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_12.jpg?raw=true" alt="Capture" /></p>

Give your project a unique name, and click the Create Project button.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_13.jpg?raw=true" alt="Capture" /></p>

Our data is now loaded as an OpenRefine project.

## Cleaning Data in OpenRefine

Our goal in this tutorial is to take the single song CSV files, combine them, and remove unnecessary columns so we have only the song lyrics. 

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_14.jpg?raw=true" alt="Capture" /></p>

To add, remove, or move columns in OpenRefine, click the arrow icon by the header. Hovering your cursor over Edit column will give you additional options for manipulating columns.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_15.jpg?raw=true" alt="Capture" /></p>

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_16.jpg?raw=true" alt="Capture" /></p>

Remove the columns that do not include song lyrics until you are left with only the “lyric” column.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_17.jpg?raw=true" alt="Capture" /></p>

Click the Export icon in the top right-hand corner of the screen to view your options for exporting the OpenRefine project.

We want to choose an export option that will work with the other text analysis programs we might want to use. Generally, text analysis tools will expect your data to be in a plain text (TXT) file. 

OpenRefine does not give us the option to export as a plain text file, so we will export as a CSV file.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_18.jpg?raw=true" alt="Capture" /></p>

Open your exported CSV file in Microsoft Excel or another spreadsheet program. 

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_19.jpg?raw=true" alt="Capture" /></p>

Click File--Save As and select a place on your computer to save the file. 

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_20.jpg?raw=true" alt="Capture" /></p>

Click the drop-down menu by Save as type to see available additional file types. Select Text (Tab delimited) to save as a plain-text file.

<p align="center"><img class=" size-full wp-image-53 aligncenter" src="https://github.com/kwaldenphd/OpenRefine-tutorial/blob/master/screenshots/Capture_21.jpg?raw=true" alt="Capture" /></p>

Open the newly-created TXT file in a text editor (Notepad on PC, TextEdit on Mac) to get a sense of how the combined lyric data is structured. 

