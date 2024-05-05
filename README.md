# Linux-touchpad
some issues solved

```
#!/bin/bash

# Disable touchpad
xinput --disable 12

# Wait for 1 second
sleep 1

# Enable touchpad
xinput --enable 12

echo "Touchpad toggled successfully"
```
