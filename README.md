# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good Cloud Engineer uses Codeblocks whenever possible.

Because it allows other to copy and paste their code to replicate or research issues

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with wuotatino (')


```
 def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

result = factorial(number)
puts "The factorial of #{number} is #{result}."
```

- When you can you should attempt to apply syntax highlighting to your codeblocks

```ruby
 def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

puts "Enter a number to calculate its factorial:"
number = gets.chomp.to_i

result = factorial(number)
puts "The factorial of #{number} is #{result}."
```
![Red cat on a sofa](https://github.com/JonKloud/github-docs-example/assets/160905603/cf9835be-c876-48f0-a113-53256dda0d51)

<img src="https://github.com/JonKloud/github-docs-example/assets/160905603/cf9835be-c876-48f0-a113-53256dda0d51" alt="Red Cat on a sofa" width="200" />

Good Cloud Engineers use codeblaocks for both Code and Errors that appear in the console.

```bash
# Define a method that raises a RuntimeError
def raise_error
  raise "This is an example error!"
end

# Call the method
raise_error
```
> Here is an example of using a codeblock for an error that appears in bash

## Step 3 - GIthub Flavoured Markdown Task Lists

Github extends Markdown to have a list where you can check off items.[3]

- [x] Finish Step 1
- [] Finish Step 2
- [] Finish Step 3

## Step 4 - Use Emojis (optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |

## References
- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) <sup>[1]</sup>
- [Sintaxis de escritura y formato básicos (GitHub Flavored Markdown Spec)](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) <sup>[2]</sup>
- [GFM - Task lists](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[3]</sup>





