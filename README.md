# WATCHIT
## _CLI TOOL_

Watchit is a straightforward command-line tool that keeps track of modifications to your JavaScript files and restarts your Node.js application whenever one is made. To keep track of file modifications and lodash, it makes use of the chokidar library.Debounce to stop your program from restarting quickly and repeatedly..

# DEPENDENCIES

- lodash.debounce: Used to limit how often a function can be called.
- chokidar: A file watcher that watches for changes in your files.
- caporal: A framework for building command-line applications.
- fs: A built-in Node.js module for working with the file system.
- child_process: A built-in Node.js module for spawning child processes.

## INSTALLATION

You can install Watchit globally on your system by running:
```sh
npm install -g watchit
```
## USAGE
To use Watchit, navigate to the directory of your Node.js application and run:
```sh
watchit [filename]
```
Replace [filename] with the name of the file you want to execute. If no filename is provided, Watchit will default to index.js.

For example, if you have a file named app.js that you want to execute, you would run:
```sh
watchit app.js
```
Watchit will launch your program and keep an eye out for any modifications to your files. Watchit will automatically restart your application if a file is added, modified, or removed.


## CONTRIBUTIONS
> Contributions are welcome! Please feel free to submit a Pull Request.
