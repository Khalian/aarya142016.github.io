Git command for terminal
```bash
git status
git add .   # to add all the files
git commit -m "message"
git push origin main
```

Run the server locally
```bash
python3 -m http.server
```

# Changes to game
```python
import asyncio
import sys

# inside the loop
await asyncio.sleep(1 / 10) # 10  frame per second
```
