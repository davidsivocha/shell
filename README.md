Shell Aliases
-------------

Useful shell commands

Clone the repo in your home dir. It should exist at `~/shell`

Add the following to your .profile or .zshrc etc

```
for file in ~/shell/*; do
    source "$file"
done
```

Delete the readme.md file from the directory `rm ~/shell/README.md`

Then Reload your terminal. 
