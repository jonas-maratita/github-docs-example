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

