# cpscript SSH script

This is the **free** and **awesome** cpscript SSH script, designed to help you to 
manage your own cPanel server!

Yes, it's free :)

## Download instructions

```shell
wget -q https://raw.githubusercontent.com/Hostert/cpanel-scripts/master/cpscript -O /usr/bin/cpscript
chmod +x /usr/bin/cpscript
```

## Running

Just call it directly (it's inside `/usr/bin` to easy things)

```shell
cpscript
```

## Usage

When you call the script without args, it will show you the help page, containing
details about every action it can do:

```shell
root@myserver [~]# cpscript

[script v1.17.0]

myserver
Wed Oct 24 16:59:45 -03 2018


        USAGE: cpscript [OPTION] [PARAM 1] ... [PARAM N]

        [OPTION]                [DESCRIPTION]

        apachestatus            Apache Status

        [...]
```

## Updating

It will auto-update when needed. New script files will be read automagically.

## Getting help and reporting a bug

Open an [issue](https://github.com/Hostert/cpanel-scripts/issues)!

### I'm seeing this strange error

```shell
/dev/fd/63: line 1: syntax error near unexpected token `newline'
/dev/fd/63: line 1: `<!DOCTYPE html>'
```

If you see something like this, you made a typo. Call the script again and copy
the option to make sure it'll work this time ;)

---

This script is free to use, copy and modify, but you should leave our name and 
links, ok? We hope it make your days easier from now!
