# FindNativeJNIMethods

This is a simple command line program that:

1. Parses an APK file
2. Enumerate all native methods
3. Converts the argument types to the native equivalent
4. Writes the result to a JSON file


## Build

```
make
```

## Usage

```
$ java -jar FindNativeJNIMethods.jar
Usage: FindNativeJNIMethods.jar <path to apk> <path to output file>
```

## Credits

This program is a simple wrapper around the [JADX][jadx] decompiler that does
all the heavy lifting.

[jadx]: https://github.com/skylot/jadx
