# jscript9.dll TypedArray/DataView Memory Corruption
Proof-of-Concept exploit for jscript9 bug (MS16-063) w/ CFG bypass

Tested on Windows 10 IE11 (modern.ie).

### Write-up
http://theori.io/research/chakra-jit-cfg-bypass

### To run
1. Download exploit/jscript\_win10\_jit.html to a directory.
2. Serve the directory using a webserver (or python's simple HTTP server).
3. Browse with a victim IE to `jscript_win10_jit.html`.
4. (Re-fresh or re-open in case it doesn't work; It's not 100% reliable.)
