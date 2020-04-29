import mdxTheme from '../theme';
export const theme = mdxTheme;

# Command Line Interface

---

We've been using the command line for a little while now.

Let's develop some context.

---

# What is Bash?

Two things:

1. An environment to run commands
2. A programming language

---

The Bash shell lets us run commands.

```
$ cd some-project
```

```
$ git clone https://github.com/some-project
```

---

Bash can also be used for programming - it has things like if/else statements!

It's not a very nice language though. We won't be learning it.

---

# What is Zsh?

Zsh is an _alternative to Bash_.

Every Mac and Linux computer comes with either Bash or Zsh pre-installed as the default "terminal environment".

---

In the past, it was quite a bit different. Over the years, the two have converged.

Nowadays there is very little difference.

---

None of the things we've seen change depending on whether you use Bash or Zsh

Differences include autocompletion, advanced configuration options.

---

# What is Node?

Node is a _javascript runtime_. It's a Javascript engine, much like the one that is built into the browser.

---

Node can be launched through Bash/Zsh:

```
$ node
```

---

This is an _interactive environment_ similar to the Chrome developer tools (like what I use in lecture).

It is not identical though. For example: `window`.

---

When you launch Node, you stop being in Bash. You've switched environments.

---

Node is an _active process_. It runs until you quit it. You can press `CTRL+C` to quit.

---

Node can also be used to _run scripts_.

```
$ node exercise-1.js
```

---

Think of this as:

- Opening `node`
- Copy/pasting the contents of the file into the JS environment
- Quitting `node`

---

## Recommended workflow

---

Most of the time, you should use Node to run scripts (`node my-script.js`). Re-run the script whenever you make a change to see the new result.

---

If you want to play with an idea, or experiment, or see what an expression evaluates to, an interactive environment (`node`) is useful.

---

Any questions?
