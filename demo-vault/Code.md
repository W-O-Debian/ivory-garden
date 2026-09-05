---
created: 2026-09-05
type: demo
tags: [ivory-garden, demo, code]
---

# Code

How Ivory Garden handles inline code and code blocks.

## Inline code

Inline code uses a warm coffee color (`#5D4037`) against a soft sand background (`#EEE6DD`). The border is subtle, so code reads as part of the paragraph without breaking flow.

Use `var(--accent)` to reference CSS variables. Use `npm install` for commands. Use `Cmd + E` for shortcuts.

## Code blocks

```python
# Python with syntax highlighting
def fibonacci(n: int) -> list[int]:
    """Generate the first n Fibonacci numbers."""
    if n <= 0:
        return []
    if n == 1:
        return [0]
    
    sequence = [0, 1]
    for i in range(2, n):
        sequence.append(sequence[-1] + sequence[-2])
    
    return sequence

# Example usage
numbers = fibonacci(10)
print(f"First 10 Fibonacci numbers: {numbers}")
```

```javascript
// JavaScript with syntax highlighting
const debounce = (fn, delay) => {
  let timeoutId;
  return (...args) => {
    clearTimeout(timeoutId);
    timeoutId = setTimeout(() => fn(...args), delay);
  };
};

// Usage
const handleInput = debounce((value) => {
  console.log('Searching for:', value);
}, 300);
```

```bash
#!/bin/bash
# Shell script example
set -euo pipefail

VAULT_DIR="${1:-.}"
THEME_DIR="$VAULT_DIR/.obsidian/themes/Ivory Garden"

if [ -d "$THEME_DIR" ]; then
    echo "Theme already installed."
    exit 0
fi

mkdir -p "$THEME_DIR"
cp manifest.json theme.css "$THEME_DIR/"
echo "Ivory Garden installed successfully."
```

```css
/* CSS with syntax highlighting */
:root {
  --ivory-bg: #FAF5F0;
  --cocoa-text: #3E2723;
  --cobalt-accent: #0B68DA;
  --gold-glow: #C49A3C;
}

.callout {
  background: var(--ivory-bg);
  color: var(--cocoa-text);
  border-left: 3px solid var(--cobalt-accent);
}
```

```json
{
  "name": "Ivory Garden",
  "version": "1.0.0",
  "minAppVersion": "1.13.0",
  "author": "Ward Skaiker (recolour) · @kepano (Minimal base)",
  "authorUrl": "https://github.com/W-O-Debian"
}
```

## Plain code block (no language)

```
This is a plain code block with no syntax highlighting.
Useful for ASCII art, diagrams, or generic preformatted text.
   ┌─────────────┐
   │  Ivory Garden │
   └─────────────┘
```

## Inline code in lists

- Use `npm install` to install dependencies
- Run `npm run dev` to start the dev server
- Deploy with `npm run build && npm run deploy`

## Code with formatting around it

Here's a paragraph with `inline code` followed by **bold**, then a code block:

```python
print("Hello, Ivory Garden!")
```

And here's the paragraph after the code block.

---

*Continue to [[Quotes and Highlights]] for the next demo.*
