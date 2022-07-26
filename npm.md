### To reset user defaults

Run this in the command line (or git bash on windows):

```
echo "" > $(npm config get userconfig)

npm config edit
```

To reset global defaults

```
echo "" > $(npm config get globalconfig)

npm config --global edit
```

If you need sudo then run this instead:

```
sudo sh -c 'echo "" > $(npm config get globalconfig)'
```
