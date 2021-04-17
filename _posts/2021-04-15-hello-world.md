---
layout: post
title:  "Hello world"
tags: [test]
---

Ok, so let's test markdown features.

# Header 1
## Header 2
### Header 3
#### Header 4

*italics* _works_

**bold** __too__

## Lists
1. First item
2. Second item
    1. Nested item
    2. Second nested item
        1. Double-nested item
3. Third item

- Unordered item
    - Intended item
        - Double intended item
- Another item

## Blockquotes

> Here we have some blockquote.
>
> Multiline included!
>
>> We can nest it too :)

## Code

First let's try C++ code:

{% highlight c++ %}
#include <iostream>

int main()
{
  std::cout << "Hello blogging world! << std::endl";

  return 0;
}
{% endhighlight %}

Now maybe Python?

{% highlight python %}
if __name__ == "__main__":
    print("Hello blogging world!")
{% endhighlight %}

What do you think? In my opinion it's pretty neat :)

## Links

Check out my [GitHub](https://github.com/Sothus/ "Best GitHub account ever!") account!

## Images

At the end of this post let's put here doge because why not?

![Everybody loves doge](/assets/2021-04-14_img1.jpg)
