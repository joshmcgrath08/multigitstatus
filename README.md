# multigitstatus

Monitor multiple Git repos in a terminal

## How to use

1. Clone this repo ([if you need help](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository))
2. Ensure its `bin` directory is on your `$PATH` ([if you need help on Linux](https://unix.stackexchange.com/questions/26047/how-to-correctly-add-a-path-to-path), [if you need help on macOS](https://apple.stackexchange.com/questions/358687/right-way-to-add-paths-to-path-in-mojave), [if you need help on Windows](https://stackoverflow.com/questions/45980107/extend-path-variable-in-git-bash-under-windows))
3. Run `multigitstatus` from a Git repo or a parent directory of Git repos, or pass the directories you want to monitor as arguments

![Usage Gif](https://www.dl.dropboxusercontent.com/s/kg0v3vu6aga6vqy/multigitstatus.gif?dl=0)

## Requirements

Care has been taken to minimize the requirements of this script. Provided that a non-ancient version of `git` is available, it should run without issue on any of the following:

- Any Linux distro with `bash`
- Any macOS version (and probably most versions of OSX)
- Windows Subsystem for Linux
