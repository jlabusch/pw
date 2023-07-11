# NAME

`pw` - copy a password from BitWarden into your clipboard

# SYNOPSIS

 - `pw list [key]`: Show the list of items available, or only items matching [key].
 - `pw <key>`: Passwords are copied into your clipboard, notes are displayed on stdout.<br/>Key can be an exact-match item ID or name, or a case-insensitive substring of a name.

# NOTES

 - Requires the BitWarden CLI (`bw`) and a recent version of `node`
 - This isn't intended to replace `bw`, just add nicer wrappers for the most common paths: finding passwords and copying them into your paste buffer.

# INSTALLATION

 -  Clone this repo and add `pw` to your path, e.g. by adding `export PATH="/path/to/pw:$PATH"` to your `.bashrc`
