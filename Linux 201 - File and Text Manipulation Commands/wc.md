https://tecadmin.net/tutorial/linux/linux-wc-command/


The Linux wc command is used to count the number of lines, words, and byte (character) in a file or input stream.

Syntax:

wc [OPITON] [FILE}
Example:

Use -l to count the number of lines in a file

    wc -l myfile.txt
Use -w to count the number of words in a file

    wc -w myfile.txt
Use -c to count the number of bytes in a file. You can use this to count character in a file

     wc -c myfile.txt
Use wc with Piped Input
You can also use wc with piped input in Linux and count the lines, words, and characters in an input data.

    cat myfile.txt | wc -lwc
Another example of wc command to count the number of lines in the output of the previous command.

    find . -name "*.log" | wc -l
Tags
