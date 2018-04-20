# scripts
Some basic shell scripts to make my life easier

### get-rootkit
Fetches rootkit

### run
Compiles and executes single code files
```
Usage: run {FILENAME} [options]
    	-i	Specify the input file to use
    	-o	Specify an expected output file to diff stdout with
    	-u	Use stdin instead of '$IN_FILE' as input
    	-s	Do a simple compile and execute
    	-r	Skip compilation and just run the class
    	-b	Specify the amount of times to run the program, and output the average runtime
    	-e	Specify a file to pipe output to
    	-c	Use color for diff (must have colordiff installed)
	-h	Show usage
```

### weather
Fetches the weather, just for fun
