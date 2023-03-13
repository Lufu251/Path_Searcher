# Path_Searcher

Allowes to search for a specific directory and return the path as a string.

Works only for Windows.


## Function:
```std::filesystem::path getDirPath(std::string dir, int searchDepth)```
- std::string dir = specify the name of the directory you want to serach
- int searchDepth = amount of layers to search

## Example:
- The path  of the executable is: c:/programm/project/main.exe
- The first searched path will be "c:/programm/project"
- If the file is not found it wil go back one layer "c:/programm/"
- ...
- If the directory is not found it will throw a runtime error.
