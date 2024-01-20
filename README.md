# Git-Status-Size

This is a small custom git command that allows you to see the sizes of all of the untracked, modified, and added files in a repo. Once installed you can call `git status-size` to get a list of file sizes in your terminal.

<p align="center"><img src="example.gif?raw=true"/></p>

## Installation

1. `git clone https://gitee/circlelq/git-status-size`
2. `cd git-status-size`
3. To invoke it anywhere you'll need to export the file into your PATH. In your script file use `export PATH="/path/to/your-script/directory:$PATH`
4. Make it into an executable with `sudo chmod +x git-status-size`

Now it should work! Go to the terminal in any repo, call `git status-size`, and you should recieve an output like the one in the gif above. If you have any files over 10mb, you will be prompted if you want to add these files to your `.gitignore`.

If your file name has Chinese characters, please enter the following command in your command line 

```shell
git config --global core.quotepath false
```

Thanks Joshua Loong for source code. https://github.com/jtloong/git-status-size

## License

MIT
