# update
my overcomplicated update/setup script for ubuntu systems.
For this to work you NEED this in your .bashrc:
```
# User specific environment
if ! [[ "$PATH" =~ "$HOME/.local/bin:$HOME/bin:" ]]
then
    PATH="$HOME/.local/bin:$HOME/bin:$PATH"
fi
export PATH
```
