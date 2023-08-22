Sure! Here's the code you provided in English:

```python
import random

def generate_path():
    directions = ["forward", "backward", "left", "right"]
    path = ""
    for _ in range(random.randint(5, 10)):
        direction = random.choice(directions)
        path += f"{direction} "
    return path.strip()

# Usage example
path = generate_path()
print(path)
```

I hope this helps! Let me know if you have any other questions.
