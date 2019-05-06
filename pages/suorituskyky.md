# Performance testing

In java, you can do performance testing of your program or a subroutine for example as follows:
```java
long start_time = System.currentTimeMillis();
< call to program or subroutine that is to be timed >
long end_time = System.currentTimeMillis();
System.out.println("Execution of the subroutine took " + (end_tiem - start_time) + "ms.");
```

```System.nanoTime()``` is also usefull if the thing that is timed is so fast that ```currentTimeMillis``` doesn't yield anything useful.

Whatever you are timing, it is a good idea to do the timing multiple (e.g. 10) times and report the mean (or median) of the execution times. Also remeber to test miltiple different types of input. E.g. for compression you could time compression of a book vs. random generated text.

When you are creating documentation for performance testing, write what you tested and try to explain the results. Don't just report numbers without proper context.
