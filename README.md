# Line profiler for lua

Simple profiler to count how much time is spent on each line of the file. Useful for optimization. For some reason I was unable to find one, so I wrote it myself.

```lua
local line_profiler = require("line_profiler")

line_profiler.start()
-- ...your code here
line_profiler.stop()

print(line_profiler.report())
```
