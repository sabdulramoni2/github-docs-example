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

<img width="500" src="https://github.com/sabdulramoni2/github-docs-example/assets/144086740/fbed585f-4484-4cc5-9219-8da6739b0684"/>

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

## Step 3 - Use Github Flavoured Task Lists

Github extends Markdown to hava e lists where you can check off items. [<sup>[3]</sup>](##external-references)

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

Github extends the functionality of Markdown to provide more alignment and table cell formatting options.[<sup>[5]</sup>](##external-references)



## External References
- [Basic writing and formatting syntax (GitHub Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#styling-text.) <sup>[1]</sup> 
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) <sup>[2]</sup>
- [GMF - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[3]</sup>
- [GTM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)<sup>[4]</sup>
- [GFM - Table (with extension)](https://github.github.com/gfm/#tables-extension-)<sup>[5]</sup>
