<strong>'commands'</strong> is a folder added to my path where I store custom scripts.  This repo shares some of these useful scripts.
<hr>
<h4>extract-assets:</h4>
<p>
	This script is helpful for unix coders building websites from ai files. It converts the AI to both SVG and PDF.   The SVG file will open faster than a straight AI (in Inkscape ofcourse), and the PDF is created so we can export raw ANSI text with no ligatures.<br>
	It takes some time to convert large AI files to SVG and PDF, so I suggest running the script in the background before actually opening files to begin coding from a design.<br>
	There may be a way to skip converting to PDF and extract the text straight from SVG, that would speed up the process.<br>
	The script runs within a directory on all AI files in the directory.  The script saves all output to a freshly made folder created upon running the script.<br>
</p>
<hr>
<h4>get-fonts-from-ai:</h4>
<p>
	Using SED this script will output the font names in use within an illustrator file.  Does not appear to work on PDF's.
</p>
