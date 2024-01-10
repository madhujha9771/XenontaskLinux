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
