Darklight Nova Core Issue: Files
====================================

Issue for [Darklight Nova Core](https://github.com/darklight-studios/darklight-nova-core)

### Function
The Files issue checks that a given file/folder, or set of files/folders have been removed.

### Use
**Note:** If you are checking a group of Files, the second argument of FileIssue.setFiles is the "name" of the group, and will be displayed as "[groupname] files have been deleted"

1. Download the latest version from the [releases](https://github.com/darklight-studios/FilesIssue/releases/) section
2. Add DNCFilesIssue.jar to your DNC build path
3. Create a `FileIssue = new FilesIssue()` variable
4. If you only want to check for a single file: `fileIssue.setFile(new File("C:\bad\file.exe"))` otherwise call: `fileIssue.setFiles(new File[] { <initialize files here> }, "Bad");`
5. Add `fileIssue` to the issues array in CoreEngine
6. Start DNC!

### License
[GPLv3](LICENSE)

### Contributors
[@IsaacJG](https://github.com/IsaacJG)
