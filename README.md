# [Cywreck Blog](https://blog.cywreck.in/)

This project is built using [Hugo](https://gohugo.io/), a fast and flexible static site generator. Hugo allows you to create static websites quickly and easily with a wide range of themes and plugins.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Hugo](https://gohugo.io/getting-started/installing/)
- [Git](https://git-scm.com/)

## Getting Started

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/CyWreck/CyWreck.github.io.git
   ```

2. **Install Hugo**:

- Follow the [installation guide](https://gohugo.io/getting-started/installing/) for your operating system.

- Verify that you have installed Hugo v0.112.0 or later.

```
hugo version
```

3. **Start the Hugo Server**:

```sh
hugo server -D
```

This will start a local server at http://localhost:1313 where you can preview your site.

## Project Structure
- [`content/`](https://github.com/CyWreck/CyWreck.github.io/tree/main/content): Markdown files for your blog posts and images.
    - [`images/`](https://github.com/CyWreck/CyWreck.github.io/tree/main/content/images):Images used in the blog
    - [`posts/`](https://github.com/CyWreck/CyWreck.github.io/tree/main/content/posts):All the blog posts in markdown format.
- [`themes/`](https://github.com/CyWreck/CyWreck.github.io/tree/main/themes): The themes directory contains one or more themes, each in its own subdirectory.. We're using PaperMod for the blog.
- [`public/](https://github.com/CyWreck/CyWreck.github.io/tree/main/public):The public directory contains the published website, generated when you run the hugo or hugo server commands. Hugo recreates this directory and its content as needed.
- [`hugo.toml`](https://github.com/CyWreck/CyWreck.github.io/blob/main/hugo.toml): hugo.toml contains configuration file for our's blog's settings.

## Creating a New Post
- To create a new blog post, use the following command:
```
hugo new posts/your-new-post.md
```
Edit the newly created file in the `content/posts/` directory.
- You can also create a new post by manually creating a file inside [`content/posts/`](https://github.com/CyWreck/CyWreck.github.io/tree/main/content/posts). The file name should be the title of the blog where every character is in lower case and words are seperated by hyphen to maintain consistency.

## Publishing Your Site
Generate the Static Files:
```
hugo
```
This command will generate the static files in the [`public/`](https://github.com/CyWreck/CyWreck.github.io/tree/main/public) directory.

### Deploy Your Site:
Use your preferred hosting service to deploy the contents of the `public/` directory. For example, you can use services like Netlify, GitHub Pages, or Vercel.

## Additional Resources
- [Hugo Documentation](https://gohugo.io/documentation/)
- [Hugo Themes](https://themes.gohugo.io/)
- [Hugo GitHub Repository](https://github.com/gohugoio/hugo)

