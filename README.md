# Preview

This is an updated version of [Yet the Books](https://github.com/Yet-The-Books/hexo-theme-yet-the-books)

| ![Home (bookshelf)](./cover/1.png) | ![Category page (directory)](./cover/2.png) |
| :----------------------------: | :------------------------------: |
| Home (Bookshelf) | Category Page (Catalog) |
| ![article page](./cover/3.png) | ![archive page](./cover/4.png) |
| Article Page | Archive Page |

# Theme Logic

| Corresponding blog logic | Corresponding book relationship |
| ------------ | ------------ |
| Home | Bookshelf |
| a category | a book |
| Category Details Page | Catalog |
| an article | an article in the table of contents |

# Demo(s)

You are welcome to submit your website by [editing this README](https://github.com/Aspiring-Writer/hexo-theme-library/edit/master/README.md)

| Site | Status |
| ------------------------------------- | ------------------------------------------------------------ |
| [Lu Benwei](https://books.nexmoe.com/) | ![Lu Benwei](https://img.shields.io/website?url=https://books.nexmoe.com/ ) |
| [Sanwei Books](https://zain-books.vercel.app/) | ![Sanwei Books](https://img.shields.io/website?url=https://zain-books.vercel. app/) |

# Usage

To install the theme, run 'git clone https://github.com/Aspiring-Writer/hexo-theme-library.git themes/library' in your terminal.

To configure the theme, copy '_config.yml' to your root folder and rename it to '_config.library.yml'

# Front-matter

| parameter | description | default value |
| :--------- | :--------------------------------------------------------- | :------------- |
| `cover` | Cover, it needs to be a picture directory or link | null |
| `order_by` | Contents are ordered according to what the article is (optional values: date, -date, title, url, ...) | theme.order_by |
| `color` | cover color (optional values: red,purple,gray,blue,green) | red |

Others: https://hexo.io/docs/front-matter

<!--
# Community
Theme exchange group: [🌙 and book themes](https://jq.qq.com/?_wv=1027&k=4sLtwk78)
-->