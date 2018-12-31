# How to Locate NotePlan Directory

NotePlan Dashboard reads files saved in the NotePlan directory. 

Users must update the directory path in each geeklet for NotePlan Dashboard to function properly.

Follow these step to locate your NotePlan directory path.

1. Open Finder and go to your NotePlan in iCloud
1. Keep Finder open and open a Terminal window
1. Click and drag the NotePlan folder onto the Terminal window
    - Terminal will display the exact path to the folder (and include all necessary escaping)
1. Select and copy this folder path
1. Paste the entire path as the **userDir** value in each geeklet

**Remember some geeklets use the Calendar or Notes folders. Be sure to following the [README.md](https://github.com/biznachio/NotePlan-Dashboard/blob/master/README.md) Set Up instructions.**
