# Fonts-4-WoW

## Custom selection of fonts for World of Warcraft

Use GetBuildInfo() method to verify the 'major.minor' version number. Run the following command in the chat window:

```ecmascript 6
/run print((select(4, GetBuildInfo())))
```

Another way to get the version number is:

```ecmascript 6
/dump select(4, GetBuildInfo())
```
