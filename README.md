# GoLang Training [![Go Report Card](https://goreportcard.com/badge/github.com/smileisak/go-training)](https://goreportcard.com/report/github.com/smileisak/go-training)

This repository contains my training path to master GoLang in one month.

Resources can be found [here](http://harrymoreno.com/2016/06/30/How-to-learn-Golang-in-1-month.html).


# Step 1: Go By Examples
Trying out [Go by Example](https://gobyexample.com/) by [@mmcgrana](https://twitter.com/mmcgrana), i've created one go file for each topic.

1. [Variables](./examples/variables.go)
1. [Constants](./examples/constants.go)
1. [For](./examples/for.go)
1. [If/Else](./examples/ifelse.go)
1. [Switch](./examples/switch.go)
1. [Arrays](./examples/arrays.go)
1. [Slices](./examples/slices.go)
1. [Maps](./examples/maps.go)
1. [Range](./examples/range.go)
1. [Functions](./examples/functions.go)
1. [Multiple Return Values](./examples/functions.go)
1. [Variadic Functions](./examples/functions.go)
1. [Closures](./examples/closures.go)
1. [Recursion](./examples/recursive.go)
1. [Pointers](./examples/pointers.go)
1. [Structs](./examples/structs.go)
1. [Methods](./examples/methods.go)
1. [Interfaces](./examples/interfaces.go)
1. [Errors](./examples/errors.go)
1. [Goroutines](./examples/go-routines.go)
1. [Channels](./examples/channels.go)
1. [Channel Buffering](./examples/channel-buffering.go)
1. [Channel Synchronization](./examples/channel-sync.go)
1. [Channel Directions](./examples/channel-directions.go)
1. [Select](select.go)
1. [Non-Blocking Channel Operations](./examples/channels-non-blocking.go)
1. [Closing Channels](./examples/close-channels.go)
1. [Range over Channels](./examples/range-channels.go)
1. [Timers](./examples/timers.go)
1. [Tickers](./examples/tickers.go)
1. [Worker Pools](./examples/worker-pools.go)
1. [Rate Limiting](./examples/rate-limiting.go)
1. [Atomic Counters](./examples/atomic-counter.go)
1. [Mutexes](./examples/mutexes.go)
1. [Stateful Goroutines](./examples/stateful-goroutines.go)
1. [Sorting](./examples/sorting.go)
1. [Sorting by Functions](./examples/sorting-by-func.go)
1. [Panic](./examples/panic.go)
1. [Defer](./examples/defer.go)
1. [Collection Functions](./examples/collection-functions.go)
1. [String Functions](./examples/string-functions.go)
1. [String Formatting](./examples/string-formatting.go)
1. [Regular Expressions](./examples/regex.go)
1. [JSON](./examples/json.go)
1. [Time](./examples/time.go)
1. [Epoch](./examples/epoch.go)
1. [Time Formatting / Parsing](./examples/time-formatting.go)
1. [Random Numbers](./examples/random.go)
1. [Number Parsing](./examples/number-parsing.go)
1. [URL Parsing](./examples/url-parsing.go)
1. [SHA1 Hashes](./examples/sha1-hashes.go)
1. [Base64 Encoding](./examples/base64.go)
1. [Reading Files](./examples/reading-files.go)
1. [Writing Files](./examples/writing-files.go)
1. [Line Filters](examples/filters/line-filter.go)
1. [Command-Line Arguments](examples/cmd/args/args.go)
1. [Command-Line Flags](examples/cmd/flags/flags.go)
1. [Environment Variables](./examples/envvars.go)
1. [Spawning Processes](examples/cmd/process/spawn/main.go)
1. [Exec'ing Processes](examples/cmd/process/exec/exec.go)
1. [Signals](./examples/signals.go)
1. [Exit](./examples/exit.go)

# Discovering Go packages:

This section is for discovering Go official or unofficial packages. It is like a sandbox for more advanced examples and tools that can be useful when doing awsome things.

1. [ssh](./examples/ssh/cmd/main.go)

    This example uses `golang.org/x/crypto/ssh` to run an arbitary commands in a remote server. May be useful when creating programs that needs to make sshing stuff in a remote server.


1. [ssh-tunneling](./examples/ssh/tunneling/main.go)

    This example will establish an ssh tunnel listening from localhost passing through a bastion to a remote server.

1. [Kubernetes go client](https://github.com/kubernetes/client-go/)
    1. [Out cluster Example](./examples/k8s/examples/out-cluster/main.go): Discovering k8s go client to list pods and nodes from outside the cluster.
