this fastfetch theme are for hoshimura himawari Fan.
And I hope that you can enjoin it! 
But the waty to config it to your computer can find with your ability or can  \/ \/ \/ \/ \/ \/ see example at down \/ \/ \/ \/ \/ \/
## Create files and folders And Setup it

You can't use it or Setup if you are not **Create file and Folder First!!!**
follow this to make it can use :
1. Download [FastFetch](https://github.com/fastfetch-cli/fastfetch) I perfer 2.41.0 version for **Windows 11 home** and don't ask what for MacOS & Linux and every Distro that wold have.
2. If download it succeed let test it with this command :
```
fastfetch
```
3. If command can use you must make `config.jsonc` from this command :
```
fastfetch --gen-config
```
4. And it make file automatically at `Directory`
```
C:\Users\<Computer Name>\.config\fastfetch\config.jsonc
```  
From this command can open `Directory` too .

5. Open `config.jsonc` and type this command
 ```
 C:\Users\<Computer Name>\.config\fastfetch\config.jsonc
```
And I perfer you to use [Visual Studio Code](https://github.com/microsoft/vscode) to open and fix `config.jsonc` and copy all of it from `config.jsonc` in repository

6. You can Setup Picture from add this at header of `config.jsonc`  :
```
"logo": {
    "type": "raw",
    "source": "<Your disk>:/<Your directory>/<you picture>.sixel",
    "width": 30,
    "height": 22 ,
    "padding": {
            "top": 3,
            "left": 1
    }
  }
```
Windows Terminal support `.sixel` only. So that tou must convert `.png` and ect. to `.sixel` with [Online free convert service](https://www.google.com/search?q=convert+image+to+sixel).

## Rename a file

**Be Careful to rename any file!!** every file name are important because, if file name are change [FastFetch](https://github.com/fastfetch-cli/fastfetch) can't output result will **go wrong** and in this case the correct file name will follow here:
`config.jsonc`
`himawa4.png`


