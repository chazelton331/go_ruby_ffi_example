### Go + Ruby via FFI
##### (or Go by itself via CLI)

Run the script `build_go_library.sh`, which will produce the library code (`libsum.so` and `libsum.h`) and an executable (`sum`).

Run the executable via the command line, like so:

```
sum 1 2 3 4 5 6
# => 21
```

Or run the code through the Ruby program `sum.rb`

```
ruby sum.rb
# => 300
```
