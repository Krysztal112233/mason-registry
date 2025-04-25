# TermurinJDK

Eclipse Temurin is the open source Java SE build based upon OpenJDK. Temurin is
available for a wide range of platforms and Java SE versions.

## How to use?

For some reason, this registry only linked `temurin-jdk-latest` to mason's bin
directory.

You can get the package path via `mason-registry` API:

```lua
-- For latest JDK
require("mason-registry").get_package("temurin-jdk-latest"):get_install_path()

-- For JDK 21
require("mason-registry").get_package("temurin-jdk-21"):get_install_path()
```
