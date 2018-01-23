# Logger
This is a logger file written in golang. It is used to log messages to multiple files or however many you want.
It logs the files in JSON format to make it standardized.
The program creates a directory with the time stamp on it for each session and saves your files in it. It also utilizes environment variables to avoid absolute paths and make the code easier to use for everyone.
It was originally written to work with a server so the file is opened once for optimization purposes even if the functions are called in a loop.
