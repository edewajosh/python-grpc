[RealPython Tutorial on Microservices](https://realpython.com/python-microservices-grpc/)

python -m grpc_tools.protoc -I ../protobufs --python_out=. --grpc_python_out=. ../protobufs/recommendations.proto