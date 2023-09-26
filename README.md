# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it easy for tech people to **copy, paste, share** code. A good **_Cloud Engineer_** uses Codeblocks whenever possible. Because it allows others to copy and paste their code to replicate or research issues.

- Use three backticks (```) to create codeblocks in markdown

```
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)
```

- When you can, apply syntax highlighting to your codeblocks

  ```Python
  def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

```bash
IndexError: list index out of range
```

### Step 2 - Using Images
Use (![])

![WhatsApp Image 2023-09-25 at 2 43 40 PM](https://github.com/KennedyNjuguna/github-docs-example/assets/88589168/a5719705-0f6e-4ec8-a8c1-d43e9640a87e)

### Step 3 - Use Github Flavored Markdown Task Lists
Github extends Markdown to have a list where you can check off items <sup>[1]</sup>

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3
- [x] Finish Step 4
### Step 4 - Using Emojis <sup>[2]</sup>

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Smile | `:smile:` | 😄 |

### Step 5 - Using Tables
```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Smile | `:smile:` | 😄 |
```




## References
- [Github Flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>[1]</sup>
- [Github Flavored Markdown Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) <sup>[2]</sup>
- [Specs Page](https://github.github.com/gfm/)
