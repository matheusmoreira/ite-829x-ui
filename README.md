# ite-829x-ui
An UI for the Linux driver ite-829x

## Dependencies
- ite-829x (https://github.com/matheusmoreira/ite-829x)
- bash
- zenity
- grep
- xargs
- sed

## GUI:
```
ite-829x-ui --gui
```

## Command line usage:
### Loading configs (for when the OS boots)
```
ite-829x-ui --load
```

### Effects rotation (for keyboard bindings)
```
ite-829x-ui --toggle -e rotate
```

### Effects selection
```
ite-829x-ui --set -e [0 to 7]
```

### Brightness toggle (for keyboard bindings)
```
ite-829x-ui --toggle -bs [up or down]
```

### Brightness selection
```
ite-829x-ui --set -bs [0 to 4]
```

### Speed toggle (for keyboard bindings)
```
ite-829x-ui --toggle -s [up, down or step ()for cycling]
```

### Speed selection
```
ite-829x-ui --set -s [0 to 3]
```

### Color selection (all keys)
```
ite-829x-ui --set -r [red] -g [green] -b [blue]
```
