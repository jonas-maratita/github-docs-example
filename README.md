# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their codes to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (`)
  Not to be confused with quotation (')

```
# Define A Person class
  class Person
    # Constructor
  def initialize(name, age)
    @name = name    # Instance variable for the person's name
    @age = age      # Instance variable for the person's age
  end

# Instance method to return a greeting
  def introduce
    puts "Hi, I'm #{@name}, and I'm #{@age} years old."
  end
end
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```ruby
# Define A Person class
  class Person
    # Constructor
  def initialize(name, age)
    @name = name    # Instance variable for the person's name
    @age = age      # Instance variable for the person's age
  end

# Instance method to return a greeting
  def introduce
    puts "Hi, I'm #{@name}, and I'm #{@age} years old."
  end
end
```

- Make note of where the backtick button is located.
- It should appear above the tab key, 
- but it may vary based on your keyboard layout.

<img width="200px" src="https://github.com/omenking/github-docs-example/assets/7776/b68b8c1e-99c3-4357-b991-cc9f29f8edb1" />

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.



```bash
Traceback (most recent call last):
        2: from /usr/bin/irb:23:in `<main>'
        1: from (irb):1
RuntimeError: This is a custom error message
```

>Here is an example of using a codeblock for an error that appears in bash.

## Step 1 - How to take screenshots

- A screenshot is when you capture a part of your screen from your laptop, desktop, or phone.
- This is not to be confused with taking a photo with your phone
- **Don't do this**

  ![Dont Do this](https://github.com/orangebadger/github-docs-example/assets/124336661/ceefa70a-396f-4858-8336-68cad04c3564)

This is what a screenshot from your computer should look like.

![Screenshot](https://github.com/orangebadger/github-docs-example/assets/124336661/e52c0b54-1b13-488a-b840-947f76d8e81c)

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items.[<sup>[1]</sup>](#references)

- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

## Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | ---|
| cloud | `:cloud:` | :cloud: |
| Cloud | `:cloud_with_lightning:` | :cloud_with_lightning: |

## Step 5 - How to create a table


You can use the following markdown format to create tables
```md
| Name | Shortcode | Emoji |
| --- | --- | ---|
| cloud | `:cloud:` | :cloud: |
| Cloud | `:cloud_with_lightning:` | :cloud_with_lightning: |
```

Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. <sup>[2]</sup>

- Make note of where the pipe character keyboard key is located.
- It should appear above the return or enter key
- but it may vary based on your keyboard layout.
<img widt="200px" src="https://github.com/omenking/github-docs-example/blob/main/assets/pipe-char.jpg" />

## References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text)
- [GFM - Task Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)<sup>[1]</sup>
- [GFM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-)<sup>[2]</sup>
