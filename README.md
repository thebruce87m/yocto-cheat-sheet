# yocto-cheat-sheet


Edit an existing recipe:

```bash

# Put the recipe in a place where it can be edited
devtool modify your-recipe-name

# Build the recipe
devtool build your-recipe-name

# Deploy to target over ssh, replace the username and ip with the targets:
devtool deploy-target your-recipe-name username@192.168.0.100

# Note, if the target has a read-only filesystem then remount it beforehand:
# mount -o remount,rw /

```
