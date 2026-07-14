# Trace-Code

**The code editor that remembers what you were doing — not just what you had open.**

Every editor restores your tabs when you relaunch. None of them restore your train of thought. Trace is built around fixing that.

> **Status: early development.** Nothing to install yet — star or watch the repo to follow along.

## The two problems

**The Monday problem.** You close your editor Friday in the middle of something. Monday morning, you spend 20 minutes re-deriving your own thinking from cryptic console.logs and a half-finished function.

**The `print("HERE 2")` problem.** Editors treat experimental garbage — debug prints, commented-out attempts, temporary hacks — exactly the same as real code. Nothing separates them, so everyone eventually commits one.

## The two features

### Where Was I

When you reopen a project, Trace restores your working context, not just your files:

- what you were in the middle of
- what you already tried that didn't work
- what you were about to do next

### Scratch Layer

A first-class layer for "just poking around" code:

- scratch code is visually separate from real code
- Trace warns you before any of it ends up in a commit
- clear the whole layer in one action when you're done

## Roadmap

- [ ] Decide the stack
- [ ] First prototype: session notes that persist per project
- [ ] Scratch layer MVP: mark lines or blocks as scratch
- [ ] Commit guard: warn when scratch code is staged

## Contributing

Too early for code contributions, but ideas and feedback are welcome — open an issue.
