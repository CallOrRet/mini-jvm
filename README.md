1.
```shell
g++ -g main.cpp classloader.cpp classviewer.cpp utils.cpp methodarea.cpp \
    heap.cpp vmstack.cpp frame.cpp executionengine.cpp stringobject.cpp \
    arrayobject.cpp classinstance.cpp classruntime.cpp -o JVM
```

3.
```shell
javac -source 1.2 -target 1.2 ./test.java
```

4.
```shell
./JVM test
```
