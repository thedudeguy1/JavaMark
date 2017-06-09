# JavaMark
JavaMark is a utility that performs a benchmark of a CPU by performing a handful of operations to load test a target CPU.

[![Build Status](https://travis-ci.org/thedudeguy1/JavaMark.svg?branch=master)](https://travis-ci.org/thedudeguy1/JavaMark)
[![StyleCI](https://styleci.io/repos/93119589/shield?branch=master)](https://styleci.io/repos/93119589)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/033401b56b974a359752656f7ab1f289)](https://www.codacy.com/app/thedudeguy1/JavaMark?utm_source=github.com&utm_medium=referral&utm_content=thedudeguy1/JavaMark&utm_campaign=badger)

### Purpose
To be completed

### How to run
If you are running this the correct way. You are guaranteed to run into a `java.lang.OutOfMemoryError` exception. To avoid this, ensure you have at least 2GB of ram available and run the software with `java -Xmx2g JavaMark`. If you have more memory available, feel free to give it to the program by changing the number in the parameter to your liking. The format is as follows: `java -XmxRAMg` and replacing 'RAM' with the available memory you will give the program.

### To Do
- [x] Implement [Sieve of Eratosthenes](https://en.wikipedia.org/wiki/Sieve_of_Eratosthenes)
- [ ] Implement lossy pi calc
- [ ] Implement [Lucas–Lehmer primality test](https://en.wikipedia.org/wiki/Lucas%E2%80%93Lehmer_primality_test)
- [ ] Add [Guava](https://github.com/google/guava)'s [Stopwatch class](http://google.github.io/guava/releases/22.0/api/docs/com/google/common/base/Stopwatch.html) for timing function calls





Notes for later:

Uses Guava for timing

[https://www.tutorialspoint.com/guava/guava_overview.htm](https://www.tutorialspoint.com/guava/guava_overview.htm)

[https://github.com/google/guava/releases/tag/v22.0](https://github.com/google/guava/releases/tag/v22.0)
