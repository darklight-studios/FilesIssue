Darklight Nova Core Issue: Files
====================================

Issue for [Darklight Nova Core](https://github.com/darklight-studios/darklight-nova-core)

### Function
The Files issue {what it does}

### Use

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
