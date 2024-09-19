## This simple website allows you to generate a package list to relocate libraries inside your JAR!

It processes everything locally, no any cloud here.

It shows only packages containing .class files, so it is more accurate than manual list creation where you could input a more common package and get something broken in future (like you shouldn't input `com.google` if you have only Guava)

Try this out: [blackbaroness.github.io/jar-relocation-list-generator](https://blackbaroness.github.io/jar-relocation-list-generator)
