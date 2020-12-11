# ICD20 Homework4

There are three test case set in this homework.

You can use `make example`, `make test`, `make bonus` to run them.

- Use float to implement real type.

Bonus:
- nested (pure) function
- string operation
- array assignment

Material:
- [mapping](http://www2.cs.uidaho.edu/~jeffery/courses/445/code-jasmin.html)
- [tutorial](http://saksagan.ceng.metu.edu.tr/courses/ceng444/link/f3jasmintutorial.html)
- [instruction](https://docs.oracle.com/javase/specs/jvms/se7/html/jvms-6.html#jvms-6.5.saload)

Note the example of `x := y + z (strings)` in [mapping](http://www2.cs.uidaho.edu/~jeffery/courses/445/code-jasmin.html):
```
java/lang/StringBuffer/append(java/lang/String;)Ljava/lang/StringBuffer;
```
should be:
```
java/lang/StringBuffer/append(Ljava/lang/String;)Ljava/lang/StringBuffer;
```

Hints:
- you may initialize the variables manually
