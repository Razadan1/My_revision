# BETTY
👋 Hi there!!!. Let's discuss **betty**

## What is Betty?🤔
Betty is a code checker. It checks if our codes are intact.
Betty also refers to **betty-style**, it is a tool that helps programmers adhere to coding rules and styles and it is a set of guidelines and conventions used in writing codes. It is also related to the **Linux Kernel Coding Style**, it is designed to ensure consistent and readable code.
Betty is a script that runs against source code files to automatically check for violations of the coding rules and styles.
Betty checks our code and raises a red flag if spaces and likely characters are misused.
The guidelines betty covers are:
- Tabs or Indentation
- Spaces
- Naming conventions
- comments and more

#### Using tools like betty helps programmers to easily collaborate on the same codebase. It improves code readability and maintainability

## Installing betty
Installing betty is very simple and doesn't take time.
### Steps to installing betty
- Step 1: Have a betty repo in which it is licensed and all rules are intact. If you don't have any, you click on [betty](https://github.com/alx-tools/Betty)
- Step 2: Go to the betty repository.
- Step 3: Clone the betty repo to your local machine.
- Step 4: cd into your betty directory.
- Step 5: Install the linter with 'sudo ./install.sh' on your terminal
- step 6: Create a new file called betty and copy the script below copy from ''' - ''' on the script

'''
#!/bin/bash

\# Simply a wrapper script to keep you from having to use betty-style

\# and betty-doc separately on every item.

\# Originally by Tim Britton (@wintermanc3r), multiargument added by

\# Larry Madeo (@hillmonkey)


BIN_PATH="/usr/local/bin"

BETTY_STYLE="betty-style"

BETTY_DOC="betty-doc"


if [ "$#" = "0" ]; then

    echo "No arguments passed."
    
    exit 1


fi


for argument in "$@" ; do

    echo -e "\n========== $argument =========="
    
    ${BIN_PATH}/${BETTY_STYLE} "$argument"
    
    ${BIN_PATH}/${BETTY_DOC} "$argument"

done
'''
- Step 7: Once saved, exit the file and change permission to apply to all users with 'chmod a+x betty'
- Step 8: Move the betty file into /bin/ or somewhere else in your $PATH with 'sudo mv betty /bin/'
Step 9: You can now type betty file_name to run the betty linter

Then your codes will be checked and if any violation occurs it is flagged by betty.

To know more about betty, you can visit this site [Dr Obed explanation on betty](https://blog.ehoneahobed.com/betty-styles-for-c-programming-explained)
