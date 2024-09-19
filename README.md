## This simple website allows you to generate a package list for relocating libraries within your JAR file!

It processes everything locally — no cloud services involved.

The tool displays only packages that contain `.class` files, making it more accurate than manual list creation. This way, you avoid potential issues that can arise from inputting broader package names (for example, you shouldn't input `com.google` if you only have Guava, as `com.google` contains other libraries as well).

Give it a try: [blackbaroness.github.io/jar-relocation-list-generator](https://blackbaroness.github.io/jar-relocation-list-generator)
