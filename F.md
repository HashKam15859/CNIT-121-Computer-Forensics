# F200: Examining a Forensic Image

Inside the files acquired from the disk image, one of the images contained the flag for this task- 'EVIDENCE'. 
File Path inside Autopsy: File Views -> File Types -> By Extension -> Images -> flag 1.bmp
![Image showing the flag found in image](1.png)

# F201: Rhino Hunt with Autopsy
### F201.1 
1. After downloading the zip file we confirm its integrity by checking the MD5 and SHA1 hash values in Power Shell. If the values match with the given values, then the zip folder is authentic and unaltered.
2. To clear the first flag, we need to simply enter the first 4 digits in the SHA1 hash value which is - 'A46F'.
![Powershell-output-of-hash-values](2.1.png)

### F201.2
The second flag is the name of the file in which a mother rhino and a baby rhino are present. This file can be found in the file path: File Types -> By Extension -> Images -> f0105864.jpg
![Mother-Rhino-And-Baby-Rhino-Image](2.2.png)

### F201.3
1. To find the flag of this part, we need to explore the deleted files, and find the .doc file from them.
2. This .doc file contains a diary entry, and as we browse through the contents of it, we find that the author threw the hard disk into the Mississippi River.
3. Since the flag is said to the location where the hard drive is currently hidden, we can say the flag is 'Mississippi River'.
![Diary-Entry-Containing-The-Location](2.3.png)

### F201.4


