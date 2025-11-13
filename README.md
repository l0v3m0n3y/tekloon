# tekloon
api for stoic.tekloon.net random quote site
# Example
```nim
import asyncdispatch, tekloon, json, strutils
let data = waitFor stoic_quote()
echo data
```

# Launch (your script)
```
nim c -d:ssl -r  your_app.nim
```
