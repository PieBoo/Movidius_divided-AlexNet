Movidius_divided-AlexNet
====
### This material for the users of Intel Movidius. A successful example of dividing Alexnet into two part and execute on Intel Movidius.

Folder 1 - "AlexNet all" is a complete network architecture. 

Folder 2 - "AlexNet - two part" is a network architecture which is divided into two parts.

Previous condition: You should install intel Movidius (NC SDK) and do *make examples*. It will download several network example including AlexNet.

The graph file is Movidius's model, generated by command like *mvNCCompile -w bvlc_alexnet.caffemodel -s 12 deploy_part2.prototxt -o graph_part2*
