[comment]: <> (Copyright 2020 H. Muller, hxmuller@gmail.com)
[comment]: <> (SPDX-License-Identifier: MIT License)

## xdg-vars Project Purpose

xdg-vars exists so the $USER may perform the following
functions using a single script without requiring an
editor:

* view the XDG base directory variables (**XDG vars**)
* set the XDG vars
* remove the XDG vars

## Using xdg-vars

xdg-vars is fully documented in the script itself. To view
the usage, just run the script without options:

```
$ ./xdg-vars
```

The script can be run as the root user to set the XDG vars
in the system .bashrc. This will set them for new users as
they are created.

## License

This project uses the MIT License, of which the full text
is viewable in LICENSE.txt
