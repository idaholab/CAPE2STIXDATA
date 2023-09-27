# CAPE2STIX Data

Due to GitHub file size limitations the ~67,000 reports generated had to be split into 100MB files.  The process to reassemble these sub-files back into the original .7z archive are as follows:

1) Download all sub-files into a directory of your choosing.

2) Execute one of the following commands to reassemble the files:

   1) For Linux: 

      ```
      cat 67k_* > 67k.7z
      ```

   2) For Windows: 

      ```
      copy /b 67k_* 67k.7z
      ```

      
