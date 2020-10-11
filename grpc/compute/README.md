- python proto
    install: https://blog.csdn.net/sunt2018/article/details/90176015
    python3 -m grpc_tools.protoc -I ./ --python_out=./ --grpc_python_out=./ compute.proto

- java proto
    protoc install: https://blog.csdn.net/u010034351/article/details/17299797
    mkdir javafile
    protoc --proto_path=. --java_out=javafile compute.proto
