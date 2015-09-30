Here are common foos I used recently

## C++

+ PileBuffer: a fixed capacity pile for buffer cache
+ BlockedQueue: a `std::queue` derivative class, blocked
+ RingQueue: a queue in a ring, fixed capacity
+ Buddy: a memory alloc indexer, used Line Segment Tree
+ Handler: a message handle with `what, arg1, arg2, obj`
+ Commons: some commons calculation or control foo
+ DroidWrapper: generate attached `env` for Android

test unit all in `test.cc`

useful macro:

+ `_POSIX_`: use pthread, mutex, semaphore etc.
+ `_OSX_`, `_COCOA_PLATFORM_`: for OS X, iOS Platform
+ `_ANDROID_PLATFORM_`: for Android Platform
+ `_DEBUG_`: see more details

How to compile:

    # OS X
    g++ -o test test.cc commons/*.cc -Iinclude -I. -std=c++11 -D_OSX_

    # Linux
    g++ -o test test.cc commons/*.cc -Iinclude -I. -std=c++11 -D_POSIX_ -lpthread

## Bash

+ dumpcc: create c++ files faster
+ dumpjni: create JNI-related c++ file faster
+ dumpmk: create Android.mk, Application.mk faster
+ dumpso: addr2line for android crash
+ genindex: generate an index.html for current folder
+ patch-gradle: patch the ndk part for gradle
+ release.sh: create a revision.h for release info
+ statch: statistics the c/c++ files line

## Python

+ ttt: online translation from youdao json data

## Makefile

+ m2h: make your markdown file into html, add header and footer

