# internsctl

Custom Linux command for various system operations.
##Overview 

`internsctl` is a custom Linux command designed to simplify various system operations. It provides functionality to retrieve information about the CPU and memory, create new users, and get details about files.
## Features

 -**CPU Information:**
  
  internsctl cpu getinfo

-**Memory Information:**

internsctl memory getinfo

-**User Operations:**
 **Create user:** internsctl user create <username>
 **List user:** internsctl user list, internsctl user list --sudo-only

-**File operation:** internsctl file getinfo <file-name> [options]

      Options:

--size, -s: Print file size.

--permissions, -p: Print file permissions.

--owner, -o: Print file owner.

--last-modified, -m: Print last modified time.

## Installation
**1. Clone the repository:** git clone command cd internsctl

**2.Make the script executable:**  chmod +x internsctl

**3.Move the script to a directory in your PATH (e.g., ~/bin/):** mv internsctl ~/bin/


## usage
# Display help
internsctl --help

# Display version
internsctl --version

# Examples
internsctl cpu getinfo

internsctl memory getinfo

internsctl user create john_doe

internsctl user list

internsctl user list --sudo-only

internsctl file getinfo hello.txt

internsctl file getinfo --size hello.txt

internsctl file getinfo --permissions hello.txt

internsctl file getinfo --owner hello.txt

internsctl file getinfo --last-modified hello.txt
