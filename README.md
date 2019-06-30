# glSnoop
An experimental graphics API tracing tool for AmigaOS 4

Work-in-progress and incomplete, pull requests welcome!

## Tracing support

glSnoop supports partial logging of:

- ogles2.library
- Warp3DNova.library

## Command-line parameters

- OGLES2: enable ogles2.library tracing
- NOVA: enable Warp3DNova.library tracing
- GUI: launch the graphical user interface
- FILTER filename: define a subset of patched functions

## Tips

glSnoop uses serial port for logging. To redirect logs
to a file (for speed), one may use the Sashimi tool:

Sashimi > RAM:MyLogFile.txt

## License

PUBLIC DOMAIN

## Thanks

Kas1e for ideas and testing.
Mason for icons.
