# Your GitHub Learning Lab Repository for Introducing GitHub

Welcome to **your** repository for your GitHub Learning Lab course. This repository will be used during the different activities that I will be guiding you through. See a word you don't understand? We've included an emoji 📖 next to some key terms. Click on it to see its definition.

Oh! I haven't introduced myself...

I'm the GitHub Learning Lab bot and I'm here to help guide you in your journey to learn and master the various topics covered in this course. I will be using Issue and Pull Request comments to communicate with you. In fact, I already added an issue for you to check out.

![issue tab](https://lab.github.com/public/images/issue_tab.png)

I'll meet you over there, can't wait to get started!

This course is using the :sparkles: open source project [reveal.js](https://github.com/hakimel/reveal.js/). In some cases we’ve made changes to the history so it would behave during class, so head to the original project repo to learn more about the cool people behind this project.

## Adding New Blog Posts

To add a new blog post to the AI Technology Blog section:

1.  **Create a new Markdown file** in the `_posts` directory.
2.  **Name the file** using the Jekyll convention: `YYYY-MM-DD-your-post-title.md`. For example, `2024-12-31-my-new-ai-article.md`.
3.  **Add frontmatter** to the beginning of the file. This is crucial for Jekyll to process the post correctly. Ensure you include:
    *   `layout: post` (to use the blog post layout)
    *   `title: "Your Engaging Post Title"`
    *   `date: YYYY-MM-DD` (the date of publication)
    *   `categories: blog` (this is important to make sure it appears in the blog section)
    *   Optionally, you can add other frontmatter like `author`, `tags`, etc.

    Example frontmatter:
    ```yaml
    ---
    layout: post
    title: "The Future of AI in Healthcare"
    date: 2024-04-01
    categories: blog
    author: "Your Name"
    ---
    ```
4.  **Write your blog content** in Markdown below the frontmatter.
5.  Commit and push your changes. Jekyll will automatically build the new post.

The new post will then appear on the blog listing page at `/blog/` and will have its own page.
