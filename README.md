# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste and share** code.
A good **Cloud Engineer** uses Codeblock whenever possible.

Because it allows to copy and paste their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (`) 
- Not to be confused with quotation (')

```
def say_hello
  puts "Hello, World!"
end

say_hello
```


- When you can you should attempt to apply syntax highlighting to you code block.

```ruby
def say_hello
  puts "Hello, World!"
end

say_hello
```

<img width="500" src="assets/githib.png"/>

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.

```bash
def generate_error
  raise StandardError, "This is a custom error message."
end

begin
  generate_error
rescue StandardError => e
  puts "Error Message: #{e.message}"
end
```
> Here is an example of using a codeblock for an eror that appears in bash.

## Step 2 - How to take screenshots.

A screensgot is when you capture a part of your screen from your laptop, desktop or phone. 
This is not to be confused with take a photo with your phone.

**DON'T DO THIS**



**DO THIS INSTEAD**

![Photo of correct image](assets/example.png)


To take a screenshots on both Macos and Windows, you can use the following hotkeys:

Taking screenshots on both macOS (formerly OS X) and Windows is quite straightforward, and each operating system provides its own built-in tools for this purpose.

### On macOS:

**1. To capture the entire screen:**
   - Press `Shift + Command (⌘) + 3` simultaneously.
   - The screenshot will be saved to your desktop by default.

**2. To capture a selected portion of the screen:**
   - Press `Shift + Command (⌘) + 4` simultaneously.
   - Your cursor will change to a crosshair.
   - Click and drag to select the portion of the screen you want to capture.
   - The screenshot will be saved to your desktop by default.

**3. To capture a specific window:**
   - Press `Shift + Command (⌘) + 4` followed by the `Spacebar`.
   - Your cursor will change to a camera icon.
   - Click on the window you want to capture.
   - The screenshot of the selected window will be saved to your desktop by default.

You can also press `Control` along with the other key combinations to copy the screenshot to your clipboard instead of saving it as a file.

### On Windows:

**1. To capture the entire screen:**
   - Press the `PrtScn` (Print Screen) key on your keyboard.
   - The screenshot is copied to your clipboard and can be pasted into an image editor (e.g., Paint, Microsoft Word) for editing or saving.

**2. To capture the active window:**
   - Press `Alt + PrtScn` simultaneously.
   - The screenshot of the currently active window is copied to your clipboard.

**3. To capture a specific portion of the screen (Windows 10 and later):**
   - Press `Win + Shift + S` simultaneously.
   - Your screen will dim, and you can then click and drag to select the portion of the screen you want to capture.
   - The screenshot is copied to your clipboard, and you can paste it into an image editor.

**4. To save a screenshot as a file (Windows 10 and later):**
   - After capturing a screenshot with the `Win + Shift + S` shortcut, it's copied to your clipboard. To save it as a file, press `Ctrl + S` while the screenshot is in your clipboard.
   - You can then choose a location and name for the file.

On both macOS and Windows, you can also use third-party screenshot capture tools for more advanced features and options, but the built-in methods should cover most basic screenshot needs.

## Step 3 - Use Github Flavoured Task Lists

Github extends Markdown to hava e lists where you can check off items. [<sup>[3]</sup>](#external-references)

- [x] Finsh step 1
- [x] Finsh step 2
- [x] Finsh step 3

## Step 4 - Use Emojis (Optional)
GitHub Flavoured Markdown (GMF) supports emoji shortcodes.
Here are some examples:

| Nmae | Shortcode | Emoji |
| --- | --- | ---|
| Cloud | `:cloud: `| :cloud: |
| Cloud with lighting|`cloud_with_lighting`| 🌩️|


## Step 5 how to create a Table
You can use the following markdown format to create tables.
```md
| Nmae | Shortcode | Emoji |
| --- | --- | ---|
| Cloud | `:cloud: `| :cloud: |
| Cloud with lighting|`cloud_with_lighting`| 🌩️|
```

Github extends the functionality of Markdown to provide more alignment and table cell formatting options.[<sup>[5]</sup>](#external-references)

- ![Photo of the Monitor](assets/Screenshot.png).
- ![Photo of the Github logo](assets/githib.png)



## External References
- [Basic writing and formatting syntax (GitHub Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text.) <sup>[1]</sup> 
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) <sup>[2]</sup>
- [GMF - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[3]</sup>
- [GTM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)<sup>[4]</sup>
- [GFM - Table (with extension)](https://github.github.com/gfm/#tables-extension-)<sup>[5]</sup>
