---
#theme: minima
layout: page
title:  "Welcome to Jekyll!"
date:   2022-01-16 20:37:06 +0100
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

Courtesy of Mathjax we can make this equation look really nice:

$$
E = mc^2
$$

And here is a Mermaid flowchart diagram showing the major steps of Pandoc file conversion:

```mermaid
flowchart LR
A(INPUT) o--reader--o B(AST) o--filter--o C(AST) o--writer--o D(OUTPUT)
```

Syntax highlighting in fenced code blocks also works as you can see here:

```haskell
main = do 
  putStrLn "Hello, world!"
```
```plantuml!
Bob -> Alice : hello world
Bob <- Alice : hi world
```
```mermaid!
pie title Pets adopted by volunteers
  "Dogs" : 386
  "Cats" : 85
  "Rats" : 35
```
```python
def timer(func):
    @wraps(func)
    def wrapper(*args, **kwargs):
        start_time = perf_counter()
        value = func(*args, **kwargs)
        run_time = perf_counter() - start_time
        logger.info(f"Finished {func.__name__!r} in {run_time:.4f} secs")
        return value

    return wrapper
```


[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/