hexdump -ve '1/1 "%.2x"' binary.bin > binary.hex
tr --delete '\n' < unfused.hex > final_unfused.hex
xxd -r -p final_unfused.hex unfused.bin

bash

- cut
- awk
- grep
  -v : invert selection
- find
- xargs
- tr
- xxd
- hexdump

  rust
- ripgrep
- fd
- hx
- gitui


emacs key binds
- ctrl-a
- ctrl-e


pip
  list
  -format
  -o, --outdated


regex
  - rust
    - fd and rg specific
  - pcre/pcre2
  - lua
