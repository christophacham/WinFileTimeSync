### WinFileTimeSync

Sync the creation and modification timestamps of all files in a specified directory on Windows.

#### Building the Tool

Ensure you have Go installed on your system. You can download it from [https://golang.org/dl/](https://golang.org/dl/).

Clone the repository or download the source code to your local machine. Open a terminal in the project directory and build the tool with:

```sh
go build -o WinFileTimeSync.exe
```

#### Running WinFileTimeSync

After building, run `WinFileTimeSync` by specifying the path to the directory containing the files you want to process:

```sh
.\WinFileTimeSync.exe -path "C:\\path\\to\\your\\folder"
```

This command updates the creation and modification timestamps of all files in the specified directory to the current time.

#### Example Use

To sync timestamps of files in `C:\\Users\\Example\\Documents`:

```sh
.\WinFileTimeSync.exe -path "C:\\Users\\Example\\Documents"
```

This will process each file in the specified folder, updating its creation and modification timestamps to the current time.
