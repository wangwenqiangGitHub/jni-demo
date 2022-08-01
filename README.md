[参考文章](https://xinchen.blog.csdn.net/article/details/118636417)
# 运行
```shell
g++ -std=c++11 -fPIC -shared NativeLibrary.cpp -o libMyFunc.so
g++ test.cpp -o test ./libMyFunc.so
javac -cp javacpp-1.5.5.jar com/bolingcavalry/javacppdemo/Test.java
java \
		 -jar javacpp-1.5.5.jar \
		 com/bolingcavalry/javacppdemo/Test.java

#运行
java -cp javacpp-1.5.5.jar:. com.bolingcavalry.javacppdemo.Test

```
