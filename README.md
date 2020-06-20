# protoc-windows-gen-plugins
Plugins to generate code from .proto files in Windows

### Example usage of php plugin:

`cd C:\protoc-windows-gen-plugins`

`protoc -I proto/ --php_out=proto --grpc_out=proto --plugin=protoc-gen-grpc=./grpc_php_plugin.exe  example.proto`


### Official documentation

https://grpc.io/docs/languages/php/quickstart/


## Install plugins from more reliable source than that git

1. Download and install http://repo.msys2.org/distrib/x86_64/msys2-x86_64-20200602.exe
2. Open installed Msys2
3. Update packages: `pacman -Su`
4. Install grpc-plugins: `pacman -S mingw-w64-x86_64-grpc`
5. Your plugins are here: *C:\msys64\mingw64\bin*


## or

1. You can just download http://repo.msys2.org/mingw/x86_64/mingw-w64-x86_64-grpc-1.29.1-1-any.pkg.tar.zst
2. Open it with zstd plugin http://facebook.github.io/zstd/
