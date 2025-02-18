# How to make this work

## Make files executable
If you wanna use all the commands in this repository:
- Clone the entire project to a directory of your choice.
- Make all the directory files executable `chmod -R +x {here the directory name}`

If you wanna use only one command:
- Create a new file with a name like `git-{....}` for consistency and copy the command code
- Make the file executable
`chmod +x {here your file name path}`

## Add directory to $PATH
Add the following line to bashrc or to zshrc file
`export PATH=$PATH:/your-git-custom-commands-directory-path`

## Source the file or start a new instance of the terminal
Everything should be ready to use when you open a new terminal or run something like `source ~/.zshrc` (change if you use bashrc)

## Running the custom commands
Everything should be ready to go, just run commands by name like
`git squash -h`
