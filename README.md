# FileManager
FileManager is a Matlab class that helps in dealing with multiple files that are stored in a nested path
where each level in the file directories has some meaning.

FileManager is object oriented. You create a FileManager object and use the methods.

f=FileManager('.'); % Matlab FileManager for the current directory
f.fileList() % Get all the files in this filemanager

Check <a href="https://blog.jcamargo.co/filemanager">my blog post</a> to learn more about the benefit of using FileManager and improve file accessing in your scripts.

FileManager is part of <a href=https://github.com/JonathanCamargo/EpicToolbox>EpicToolbox</a> but this is a mirror repository for cases where the use of FileManager
is required without other tools in EpicToolbox, e.g. when the data is not stored as tables with Header column. I recommend installing and using EpicToolbox to still use FileManager 
and have access to more useful functions. If you know you don't need it you can clone and use FileManager from this mirror.

** Install **
Copy the @FileManager folder to a place that is under your Matlab path, or add the parent location of @FileManager to path.


