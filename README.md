# github
A github library to interface with git directly. 

Github Functions

```js
add(filepath, opts) // //Git add a file to the local filesystem.
checkStatus() // //Check the status of the entire project by getting the status of each file.
clone(opts) // //Clone a repository to the local filesystem.
commit(message, opts) // //Git commit the changes in the local filesystem.
diff(commitHash1, commitHash2) // //Get the difference between two commits, including added, removed, and modified files.
exists(filename = '') // Check if a file or directory exists in the filesystem.
fetch(opts) // Fetch updates from the remote repository.
getAll(rootDir, existing = []) // Get a list of all files in the local filesystem.
getAllItems() // Get all items from the collection, including their metadata and content.
getAuthUrl() // Get the URL of the repository with username and password for basic authentication.
getCommitStatusWithDiff() // Get the commit status with the difference between the remote and local commits.
glob(g) // Get all filenames that match a glob pattern in the local filesystem.
init() // Initialize the Git repository by pulling changes if the repository exists or cloning it if it doesn't.
listServerRefs(opts) // Get a remote list of Git references.
log(opts = {}) // Get the Git log for the repository.
mkdirp(dirname) // Recursively create a directory.
push(opts) // Push changes from the local filesystem to the remote repository.
read(filename, encoding) // Read the contents of a file from the local filesystem.
rm(filepath, opts) // Remove a file or directory from the local filesystem.
status(opts = {}) // Get the Git status of the project.
write(filename, contents) // Write contents to a file in the local filesystem.
```
