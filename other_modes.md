>>Mode :	Simple Work
1. rb   :	Opens a file in read mode as binary data. Useful for reading images, PDFs,and 
            other binary files
2. wb   :   Opens a file in write mode as binary data. Creates a new file or overwrites an    
            exisisting one.
3. ab   :   Opens a file in append mode as binary data. Adds new binary data at the end of     
            the file
4. rb+  :   Opens a binary file for both reading and writing without truncating it.
5. wb+  :   Opens a binary file for both reading and writing, but overwrites existing content.
6. ab+  :   Opens a binary file for reading and appending. New data is added at the end.
7. rt   :   Opens a file in text mode for reading. This is the default mode when using open().
8. wt   :   Opens a file in text mode for writing. Creates a file or overwrites existing content.
9. at   :   Opens a file in text mode for appending. Adds new content at the end.
10. r+t :	Opens a text file for both reading and writing without truncating it.
11. w+t	:   Opens a text file for both reading and writing, overwriting existing content.
12. a+t	:   Opens a text file for reading and appending. New content is added at the end.

>Note: 
t means text mode, which is the default. You can also combine it with other modes, such as r+t or w+t.