# 0.3.0
- [#29] *MultiJson* usage. *Oj* gem installation is suggested for best performance

# 0.2.7
- [#28] Handle lack of Go processes gracefully at exit
- [#28] Don't validate GOPATH
- [#28] Validate Go executable only when compilation is needed

# 0.2.6
- [#13] Meaningful exception types
- [#20] Speed up Go Quartz process boot time
- [#22] Handle large buffers

# 0.2.5
- [#12] Make seeds in Go process wrappers threadsafe
- Destroy socket files upon exit inside Go processes
- Upgrade development environment to Ruby 2.1.5 and Go 1.4
- Use long suffixes when naming domain sockets
