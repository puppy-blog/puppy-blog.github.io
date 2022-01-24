# Guide to Contributing

If you have further questions, open a [GitHub Issue](https://github.com/puppy-blog/puppy-blog.github.io/issues).

## Who can write for the blog?

Anyone in the PuPPy community, broadly defined.

## What can I write about?

This blog is an outlet for members of the PuPPy community to share with the wider Python world. Anything that might be of interest to that audience is welcome.

Some ideas:

- A couple paragraphs about something you learned recently
- A deep dive into a subject you love
- A written adaptation of a talk
- A work-in-progress side project

This blog is an outlet to archive or take a deeper dive into the things we are passionate about.

## Who decides what goes in the blog?

We strive to keep the blog as "open" as possible. For this reason, submissions, the editing process, and publication are conducted via a public GitHub repository. Volunteer editors and maintainers exist to:

- Ensure the [PuPPy Code of Conduct](https://www.pspython.com/pages/code-of-conduct/) is followed.
- Encourage individuals to submit posts.
- Make suggestions about draft posts.
- Manage the technical aspects of publishing the blog.

Editors and maintainers should default to "yes" on proposed blog post ideas, provided that the author follows the [Code of Conduct](https://www.pspython.com/pages/code-of-conduct/).

## I have an idea. How do I submit something?

1. Fork the [blog’s GitHub repository](https://github.com/puppy-blog/puppy-blog.github.io).
2. Create a new branch for your post.
3. Write your post in a [format supported by Jupyter Book](https://jupyterbook.org/file-types/index.html): reStructuredText, Markdown, or Jupyter Notebooks.
4. Save your post in the `/posts/drafts/` directory, commit and push your changes to your fork.
5. Open a Pull Request on the GitHub repo.
6. Editors will review your post and may leave feedback or suggestions.
7. Add additional commits to address the feedback.
8. When you are satisfied with any revisions or updates, tag the editors in a comment on your PR.
9. When you have approval from two editors, your post will be published.

## Style and Format

The blog’s theme sets many of the default stylistic aspects of the blog. Beyond that, you are welcome to write your content in whatever way you choose.

There is a basic template for a Markdown post in `/drafts/template.md`.

The blog is built with the [Jupyter Book](https://jupyterbook.org/) framework. Jupyter Book offers many nice features built-in:

- Content can be written in [Markdown, reStructuredText, or Jupyter Notebooks](https://jupyterbook.org/file-types/index.html)
- [Admonitions](https://jupyterbook.org/content/content-blocks.html#notes-warnings-and-other-admonitions) (e.g., “Note” or “Warning” callout boxes)
- “Copy” button automatically added to code blocks
- [Margin content](https://jupyterbook.org/content/layout.html#sidebar-content)
- [Footnotes](https://jupyterbook.org/content/content-blocks.html#footnotes)
- [Interactive plotting](https://sphinx-book-theme.readthedocs.io/en/latest/notebooks.html#interactive-outputs)

You can see more in the [Jupyter Book documentation](https://jupyterbook.org/content/content-blocks.html).

### Images

Put images in the `/assets/images/<year>` directory. In your post, you can refer to them in a Markdown link. For example, the following will display the Python logo.

```markdown
![python logo](../assets/images/2022/python-logo.svg)
```

![python logo](../assets/images/2022/python-logo.svg)

### Comments

You can choose to enable or disable comments on your post by adding (or not) the following snippet at the end of your post.

````md
```{raw} html
<script src="https://utteranc.es/client.js"
        repo="puppy-blog/puppy-blog.github.io"
        issue-term="pathname"
        label="blog-comment💬"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
```
````

## Editors’ checklist

The editors will use this list of questions to decide when a post is ready for publication. Final responsibility for content is assumed by the author.

- [ ] Does the post adhere to the Code of Conduct?
- [ ] Is the post of interest to the community?
- [ ] Does the post appear free of obvious typos?
