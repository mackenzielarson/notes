# Notes

### Entry Template


__command__ - _Description_

__Examples:__

```
bash code in here
```
---

## File Management

__mv__ - _Move file or Rename file_

__Examples:__

```
mv sourceFile destinationFile
mv sourceFile destinationLocation
mv myFile.txt myFolder/
```
---

__cp__ - _Copy file or folder_

__Examples:__

```
cp filename.cpp myCopy.cpp
cp -r myFolder/ myNewFolder
```
---

__rm__ - _remove and delete files (file and directories)_

__Examples:__

```
rm file1 file2 file 3
rm -r dir1 dir2
```
---

__rmdir__ - _remove and deletes empty directories_

__Examples:__

```
rmdir lab03
rmdir junkdirectory
```
---

__ln -s__ - _Symbolic Link refers to another file by its path_

__Examples:__

```
ln -s myfile mysoftlink 
```
---

__scp__ - _Securely coppies files_

__Examples:__

```
scp myfile
```
---

__pwd__ - _Prints the absolute working path of your current working directory_

__Examples:__

```
$pwd
/users/smith/mydir
```
---

__ls__ - _(hidden files and files starting or ending with specific patterns like all files ending in txt or all files starting with the letter b)_

__Examples:__

```
ls mydirectory 
ls myfiles
```
---

__tar__ - _Saves many files together into a single tape or disk archive, and can restore individual files from
       the archive.-

__Examples:__

```
tar -cf archive.tar foo bar
              # Create archive.tar from files foo and bar.

       tar -tvf archive.tar
              # List all files in archive.tar verbosely.

       tar -xf archive.tar
              # Extract all files from archive.tar.
```
---

## File Transfer

__curl__ - _Transfer a url_ 

__Examples:__

```
curl [options] url 
```
---

__wget__ - _The non-interactive network downloader_

__Examples:__

```
wget
```
---


__scp__ - _secure copy (remote file copy program)_

__Examples:__

```
scp 
```
---

__rsync__ - _a fast, versatile, remote (and local) file-copying tool_

__Examples:__

```
rsync thatfile.txt > thisdir
```
---

## Pipe tools

__cat__ - _Views files in their entierty that prints its files to standard output concatenating them_

__Examples:__

```
cat myfile.txt
```
---

__sort__ - _Sorts lines of text files_

__Examples:__

```
sort myfile.txt
```
---

__uniq__ - _Report or omit repeated lines_

__Examples:__

```
uniq myfile.txt 
```
---

__grep__ - _Print lines matching a pattern_

__Examples:__

```
grep diff myfile.txt
grep 1 myfile.txt
```
---