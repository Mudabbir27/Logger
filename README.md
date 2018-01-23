# Logger
This is a logger file which is used to log msgs to multiple files or however many you want.
It logs the files in JSON format to make it standardized.
The program creates a directory with the time stamp on it for each session and saves your files in it.
It was originally written to work with a server so the file is opened once for optimization purposes even if the functions are called in a loop.
