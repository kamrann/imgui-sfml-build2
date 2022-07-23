# imgui-sfml

`build2` packages for the [imgui-sfml](https://github.com/eliasdaler/imgui-sfml) framework backend for the [Dear ImGui](https://github.com/ocornut/imgui) library.

## Usage

Simply add the backend package to your `manifest`.
Note that `libimgui-sfml` package is a framework backend, which means it is all self-contained and you do not need any additional render or platform backend.

```
depends: libimgui-framwwork-sfml
```

Headers are included without any prefix, for example:

```c++
#include <imgui-SFML.h>
```

See also the `imgui-sfml-examples` package for examples on how to build executables with the package.
