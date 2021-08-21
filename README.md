This is a fork of https://gitlab.com/mattbas/Qt-Color-Widgets.

### Dynamically link in Qt projects

```
$ mkdir build && cd build
$ cmake -DCMAKE_BUILD_TYPE=Debug/Release -G "MinGW Makefiles"
$ mingw32-make QtColorWidgets -j<numberOfProcessorCores>
```

``BUILD_TYPE`` differences:

- **Debug**: Creates a library with a "d" suffix
- **Release**: Default library build, no suffix

## License

Still the same as https://gitlab.com/mattbas/Qt-Color-Widgets#license!