## SHORTCUTS

Ctrl + C : halts the current command
Ctrl + Z : stops current command, resume with fg in foreground or bg in background
Ctrl + D : log out of current session, similar to exit
Ctrl + W : erases one word in the current line
Ctrl + U : erases the whole line
Ctrl + R : bring up a recent command
!! or Up + Enter : repeats the last command
exit : log out of current session

## FILE COMMANDS

ls : directory listing
ls -al : formatted listing with hidden files
cd *<dir> : change directory to <dir>
cd : change to home
pwd : show current directory
mkdir <dir> : create a directory <dir>
rm <file> : delete <file>
rm -r <dir> : delete directory <dir>
rm -f <file> : force remove <file>
rm -rf dir : force remove directory <dir> (can be a dangerous command)
cp <file1> <file2> : copy <file1> to <file2>
cp -r <dir1> <dir2> : copy <dir1> to <dir2>, create <dir2> if non-existent
mv <file1> <file2> : rename or move <file1> to <file2> if <file1> exists
ln -s <file> <link> : create symbolik link <link> to <file>
touch <file> : create or update <file>
cat > <file> : places standard input into <file>
more <file> : output the contents of <file>
head <file> : output the first 10 lines of <file>
tail <file> : output the last 10 lines of <file>
tail -f <file> : output the contents of <file> as it grows, starting with last 10 lines

## SEARCHING

grep <pattern> <files> : search for <pattern> in <files>
grep -r <pattern> <dir> : search recursively for <pattern> in <dir>
<command> | grep <pattern> : search for <pattern> in the output of <command>
locate <file> : find all instances of <file> 
*
