# Linux_sh_Bash_Practice
Practice environment for linux and bash scripting

# Linux Command Line Cheat Sheet and Reference Card
### Getting Help
man [command] Read the manual for a given command.
command ­h Ask the command for help.
command ­­help Ask the command for help.
Listing Files and Directories
ls PATH List the file or directory at PATH.
ls PATH1 PATH2 List both [PATH1] and [PATH2].
ls ­l PATH Long listing format.
ls ­a PATH Show all files, including hidden files.
ls ­R PATH Recursive listing.
ls ­F PATH Show type of each file.
"/" = directory, "*" = executable, "@" = link
### Changing Directories
cd PATH Change into the directory at PATH.
cd Change into your home directory.
cd .. Go up one directory.
cd ­ Change to the previous directory.
pwd Display the full path to your current
directory.
### Creating and Removing Directories
mkdir PATH Create a directory at PATH.
mkdir ­p PATH Create the parent directories if needed.
rmdir PATH Remove directory at PATH. The directory must be
empty. If it is not, use rm ­rf PATH.
rm ­r PATH Recursively remove all files and subdirectories
starting at PATH
rm ­i PATH Run in interactive mode.
### Copying Files and Directories
cp SRC DEST Copy SRC to DEST.
cp SRC1 [SRCN..] DIR Copy SRC1 into DIR.
cp ­i Run in interactive mode.
cp ­r SRC DEST Copy SRC recursively to DEST.
### Moving and Renaming Files and Directories
mv SRC DEST Move SRC to DEST.
mv ­i SRC DEST run in interactive mode.
mv OLDFILE NEWFILE Rename OLDFILE to NEWFILE
### Deleting Files
rm FILE Remove FILE.
rm ­r DIR Remove the DIR and its contents recursively
rm ­rf FILE Force removal and never prompt for
confirmation.
### Viewing Files
cat FILE Display the contents of FILE.
more FILE Browse through a text FILE.
less FILE Has more features than more.
head FILE Output the beginning (or top) portion of FILE.
tail FILE Output the ending (or bottom) portion of FILE.
Editing Files
nano FILE Use the nano editor to view or modify FILE.
