<h1>Hash values</h1>



<h2>Description</h2>
In this lab, I created and evaluated the hash values for two files. I used Linux commands to calculate the hash of two files and observe any differences in the hashes produced. Then, I determined if the files are the same, or different.
<br />


<h2>Practical experience gained in this Lab</h2>

- <b>Computing hashes using sha256sum</b> 
- <b>Displaying hashes using the cat command</b>
- <b>Comparing hashes using the cmp command</b> 


<h2>Environments Used </h2>

- <b>Qwiklabs</b> 

<h2>Lab walk-through:</h2>

<h2>Task 1: Generate hashes for files </h2>
In this task, I need to display the contents of each of these files. I generated a hash value for each of these files and send the values to new files, which I used to examine the differences in these values later.
 <br/> <br />
(1) I used the command "ls" to list the contents of the directory. <br/>
(2) I used the commands "cat file1.txt" and "cat file2.txt"to display the contents of file1.txt and file2.txt <br/>
(3) I used the commands "sha256sum file1.txt" and "sha256sum file2.txt" to generate the hashes of both file1.txt and file2.txt.  
<br/> <br/> <p align="center">
<img src="https://imgur.com/orl8rco.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br /> <br />

<h2>Task 2: Compare hashes </h2>
In this task, I wrote the hashes to two separate files and then compared them to find the difference.
<br/> <br />
(4) I used the commands "sha256sum file1.txt >> file1hash" and "sha256sum file2.txt >> file2hash" to generate the hashes of file1.txt and file2.txt and send the output to the new files called file1hash and file2hash. <br/>
(5) I used the commands "cat filehash" and "cat file2hash" to display the hash values in the file1hash and file2hash files. <br/>
(6) I used the command "cmp file1hash file2hash" to highlight the differences in the file1hash and file2hash files. 
<br /> <br /> <p align="center">
<img src="https://imgur.com/gtScX9J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
<br /> <br />
