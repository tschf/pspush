# pssync

Utilises the `gdrive` tool to push and pull a file from/into google drive.

Program flow, when you login, run pspull (Pulls the file from Drive); When you make changes to the file, push the changes back into drive - creating a revision.

## pspull arguments

1. The Google Drive file ID
2. The directory to save the file. The file name will be the same as it is in Google Drive

example:

```
./pspull 0B9RLGPH $HOME
```

## pspush arguments

1. The Google Drive file ID
2. The input file to by sent back to that file ID

example:

```
./pspush 0B9RLGPH /home/trent/myfile.sln
```

# Author

Trent Schafer, 2017

# License

The Unlicense
