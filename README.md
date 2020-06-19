# protoc-windows-gen-plugins
Plugins to generate code from .proto files in Windows

## Example usage of php plugin:

cd C:\protoc-windows-gen-plugins

protoc -I proto/ --php_out=proto --grpc_out=proto --plugin=protoc-gen-grpc=./grpc_php_plugin.exe  example.proto


## Official documentation

https://grpc.io/docs/languages/php/quickstart/