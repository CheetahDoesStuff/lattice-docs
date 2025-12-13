## Note!

This guide assumes you are on desktop. Everything also works on mobile, though some UI elements (buttons, layout, etc.) may look a bit different.

---

## What you need

To contribute to the Lattice docs, you only need:

* A GitHub account
* A web browser

That’s it.

---

## Getting started

All pages in the docs are written in **Markdown**. Markdown uses simple characters to format text, for example *italic text* or **bold text**.

If you’re new to Markdown, this is a great place to start:

* [https://www.markdownguide.org/basic-syntax/](https://www.markdownguide.org/basic-syntax/)

It doesn’t cover everything, but Markdown is very popular, so it’s easy to search for how to do more specific things (links, tables, code blocks, etc.).

There is also custom "shortcodes" that are harder to search up but luckily for you, ive copied over some of the official documentation for it, so check out the shortcodes section below in the menu/navigation!

---

## Where do I write?

The docs live in a GitHub repository. How you edit them depends on whether you have **direct edit permissions** or not.

There are two cases:

* Editing **with permissions** (directly on the repo)
* Editing **without permissions** (via a fork and pull request)

Both workflows are very similar — the main difference is how your changes get merged back into the main repository.

---

## With permissions

### Who this applies to

* CheetahDoesStuff (repo owner)
* Gunslinger Zach
* (soon) Mayaafox
* (soon) Opalblade

If you’re on this list, you can edit files directly.

### Editing an existing page

1. Go to the docs content folder:
   [https://github.com/CheetahDoesStuff/lattice-docs/tree/master/content/docs](https://github.com/CheetahDoesStuff/lattice-docs/tree/master/content/docs)

2. Navigate through the folders to find the page you want to edit. Nested pages on the website are nested in folders here as well.

3. **Do not edit `_index.md` files.** They usually don’t contain visible text and changing them can break site structure or navigation.

4. Click the Markdown file you want to edit. You’ll see a preview of the file.

5. In the top-right of the file view, click the **pencil icon** to start editing.

6. Make your changes.

7. Click **Commit changes…**, write a short description of what you changed, and confirm.

Your changes will be live on the site in about 1–5 minutes.

---

## Without permissions

### Who this applies to

* Everyone else

If you don’t have permissions, you can still contribute — it just takes one extra step.

### How this differs from the permissions workflow

* You **cannot** edit the main repo directly
* You work in your own copy (a fork)
* Your changes are merged via a **pull request**

The actual editing process is almost identical.

### Editing an existing page

1. Go to the main repository:
   [https://github.com/CheetahDoesStuff/lattice-docs/](https://github.com/CheetahDoesStuff/lattice-docs/)

2. Click **Fork** (top-right). This creates a copy of the repo under your GitHub account.

3. In your fork, navigate to `content/docs` and find the file you want to edit.

4. Just like in the permissions workflow:

   * Don’t edit `_index.md`
   * Click the file
   * Click the pencil icon
   * Make your changes
   * Commit them

### Getting your changes merged

1. After committing, GitHub will usually show a **“Compare & pull request”** button. Click it.

2. Write a short description of what you changed and why.

3. Submit the pull request.

A maintainer will review it. If everything looks good, your changes will be merged and will appear on the site shortly after.

---

## Summary

* Both workflows use the **same files** and **same editing steps**
* The only real difference is:

  * With permissions: you commit directly
  * Without permissions: you fork and open a pull request

If you’re unsure about anything, open a pull request anyway — feedback is easier than guessing wrong. If you dont know how to do some specific task, like creating new files / sub-categories of files then DM CheetahDoesStuff on discord for technical help.