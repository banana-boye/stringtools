# CC_stringtools
String tools is a simple tool to add a bit more of common string manipulation functions into cc

[Wiki](https://github.com/banana-boye/CC_stringtools/wiki/String-methods)

### Using stringtools

Install the API
```bash
wget https://raw.githubusercontent.com/banana-boye/CC_stringtools/refs/heads/main/stringtools.lua stringtools
```

Add the string tools to your file
```lua
require("stringtools")()
```

Done! Now you can work as if it was always a part of the main string function, here's some examples:
```lua
local amount_of_l = string.count("Hello world, how are you?", "l")
print("There is a total of "...amount_of_l.." l\'s in the string!") --> There is a total of 3 l's in the string!
```
