# PDF Merge & Split in Offline
Offline tool to merge &amp; split pdf files working on Windows, Linux and Mac operation systems. It uses Java, so to run the app you need to have installed Java on you machine.

## How to use
There are two tabs
1) Merge - merge 2 pdf files into 1
2) Split - split 1 pdf file into 2 or more pdf files

### Merge

You select two pdf files and give a name to output pdf file. It generates new pdf fie in the same folder.


### Split

You select a pdf file to split. Specify page number where split should happen. New files will be generated with predefined names *spltted_0*, *splitted_1*, etc...

**Example:**
```
Keep in mind if you have pdf file with 10 pages and you specify number _3_. The split happens every 3rd page. The output will be 4 pdf files where three files with three pages and one pdf file with one page.
```

PS. unfortunately there is problem with relative path on Mac machines, so please use folders. You need to perform actions inside the folder. the generated file always appear on one directory higher that you are.
