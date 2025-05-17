# dl
Downloads the specified directories and files from a git repo.

### Usage
```sh 
gitzeug dl -u <URL> -o <PATH> -f <FILES>
```
Args:
 - `-u, --url <URL>`: The URL of the git repo.
 - `-o, --output <PATH>`: The ouput/destination directory.
 - `-f, --files <FILES>`: Directories and files to download.

### Example
```sh 
gitzeug dl -u https://github.com/thaemisch/gitzeug.git -o . -f src,Cargo.toml
```
