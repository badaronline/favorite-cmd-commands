# **favorite-cmd-commands**
## _**Some Important Bash Commands**_

## $ mkdir FolderName
To create a folder / directory in current location.

## $ mkdir .FolderName
To create a hidden folder / directory in current location.

## $ mkdir -p Folder/ChildFolder/GrandChildFolder
To create a multiple nested folders in one time.

## $ touch FileName.txt
To create a new file with any given extension. It could be a text file or an HTML file or any other sort of file.

## $ touch .FileName.txt
To create a new hidden file with any given extension. It could be a text file or an HTML file or any other sort of file.

## $ code FileName.txt
To open the mentioned file in VScode. It works only when Visual Studio Code is installed.

## $ echo "First Message" > fileName.txt
To write anything in the first line of the file.
If there is anything already written in the file, that will be removed and this new text will be added instead.

## $ echo "Second Message" >> fileName.txt
To write also in the mentioned file but it will write the text in the second line of the file.

## $ cat FileName.txt
To read the content of the file and display it in the Bash.

## $ attrib +h ABC.txt / $ attrib +h ABC         
To hide existing file/folder. 

## $ attrib -h ABC.txt / $ attrib -h ABC         
To un-hide existing file/folder. 

## $ rm -rf folderName
To remove the folder with all the files and folders inside it.

## $ rm Filename.txt
To remove the file. 

## $ ls
To list all files and folders in the current directory.

## $ ls -a
To list all visible as well as hidden files and folders in the current directory.

## $ cp -r FolderName1 FolderName2
To copy the content of FolderName1 and paste inside FolderName2.

## $ mv FolderName1 FolderName2
To move (cut and paste) FolderName1 inside FolderName2.

## _**Some Important GIT Related Commands**_

## $ git init
To Create / initial a git repository.

## $ git add fileName
To add file to a new commit.

## $ git add .
To add all files and folders to a new commit.

## $ git commit -m "Commit Message"
To commit the file with a text message.

## $ git checkout -- fileName
To discard any changes and reset / restore the file to the previous commit.

## $ git log
To Show all commits.

## $ git log -p
To show all commits and contents of the files.

## _**Some Important GITHUB Related Commands**_

## $ git clone
To clone an existing online repository on your local computer.

## $ git push
To upload commits to an online repository.

## $ git pull
To download commits form an online repository.