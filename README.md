Download Link: https://assignmentchef.com/product/solved-cs2028-homework-1-files-and-structures
<br>
The objective of this homework is to create structures, read from, create and write to files using C++..  This assignment will incorporate arrays

<strong>Scenario: </strong>

You are a programmer tasked to take the plain text from a series of formatted files and create a library card catalog file and a statistics file.

<strong>Requirements: </strong>

<ol>

 <li>Ask the user for the name of the file to be processed.</li>

 <li>Attempt to open the file of the given name. If unsuccessful, it should output an error message and prompt the user to enter another file name.</li>

 <li>With the file open, read into a Structure:

  <ol>

   <li>Title</li>

   <li>Author full name (the name is stored in the file as First and Last name with a space between)</li>

   <li>Word Count (total number of words in the book contents. A word is one or more letters</li>

  </ol></li>

</ol>

(not counting punctuation) separated by a space so ice cream is considered 2 words)

<ol>

 <li>Letter frequency (this is the number of times each letter has been encountered in the book contents)</li>

 <li>Line Count (count of new line characters in the contents section)</li>

</ol>

<ol start="4">

 <li>Save this information in the file CardCatalog.txt

  <ol>

   <li>If the file doesn’t exist, create it.</li>

   <li>If the file does exist, append to it.</li>

   <li>Leave a blank line between each card catalog entry.</li>

   <li>The file should be human readable such as (is should be similar but not necessarily the same as the following*):</li>

  </ol></li>

</ol>

Title: Moby Dick

Full Author: Herman Melville

Author First Name: Herman

Author Last Name: Melville

Word count: 375

Line count: 17

<ol start="5">

 <li>Ask the user if they want to see the letter frequency. If they agree, it should look like*: Moby Dick letter frequency:</li>

</ol>

a: 0.0762% b: 0.0 % c: 0.0253% d: 0.0405%

<ol start="6">

 <li>Ask the user if they wish to process another book. If they do, repeat requirement 2.  If</li>

</ol>

they don’t, program should quit.  This should not add to previous results.

(*) <em>The numbers shown heer are not necessary correct</em>