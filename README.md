# Relevant Notes

To locally build the wesbite and host, use the command `hugo server` and then open the web server hoster at `http://localhost:1313/`. 

The relevant folders are:

1. Config/\_default: Meta parameters govern the layout, font type, font size and other relevant parameters.
2. Content: Everything related to the content of the website. 
	1. home/aboud.md - edit this file to edit the biography
	2. home/featured.md - edit this file to edit the recent publication on the website
	3. home/publications.md - edit this file for publication


## Editing the content


Some quick notes about editing the content

1. Layout of the webite - To edit the sequence in which the sections appear, edit the `weight` paramter within each yaml file inside the `content/home/` directory.
2. Font of the website - The Font can only be changed website wide by editing the `font_size` paramter in `config/_default/params.yaml` file. To edit content specific font related parameters, we need to edit the CSS. 
3. Header and Footer: To edit the sections and their sequence we need edit the `config/_default/menus.yaml` file. 


<!-- # Old Hugo Readme

## [Hugo Academic Theme](https://github.com/wowchemy/starter-hugo-academic)

[![Screenshot](./preview.png)](https://wowchemy.com/hugo-themes/) -->

The Hugo **Academic Resumé Template** empowers you to easily create your job-winning online resumé, showcase your academic publications, and create online courses or knowledge bases to grow your audience.

[![Get Started](https://img.shields.io/badge/-Get%20started-ff4655?style=for-the-badge)](https://wowchemy.com/hugo-themes/)
[![Discord](https://img.shields.io/discord/722225264733716590?style=for-the-badge)](https://discord.com/channels/722225264733716590/742892432458252370/742895548159492138)  
[![Twitter Follow](https://img.shields.io/twitter/follow/wowchemy?label=Follow%20on%20Twitter)](https://twitter.com/wowchemy)

️**Trusted by 250,000+ researchers, educators, and students.** Highly customizable via the integrated **no-code, widget-based Wowchemy page builder**, making every site truly personalized ⭐⭐⭐⭐⭐

Easily write technical content with plain text Markdown, LaTeX math, diagrams, RMarkdown, or Jupyter, and import publications from BibTeX.

[Check out the latest demo](https://academic-demo.netlify.app/) of what you'll get in less than 10 minutes, or [get inspired by our academics and research groups](https://wowchemy.com/creators/).

The integrated [**Wowchemy**](https://wowchemy.com) website builder and CMS makes it easy to create a beautiful website for free. Edit your site in the CMS (or your favorite editor), generate it with [Hugo](https://github.com/gohugoio/hugo), and deploy with GitHub or Netlify. Customize anything on your site with widgets, light/dark themes, and language packs.

- 👉 [**Get Started**](https://wowchemy.com/hugo-themes/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- 💬 [Chat with the **Wowchemy research community**](https://discord.gg/z8wNYzb) or [**Hugo community**](https://discourse.gohugo.io)
- ⬇️ **Automatically import your publications from BibTeX** with the [Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli)
- 💡 [Suggest an improvement](https://github.com/wowchemy/wowchemy-hugo-themes/issues)
- ⬆️ **Updating?** View the [Update Guide](https://wowchemy.com/docs/hugo-tutorials/update/) and [Release Notes](https://github.com/wowchemy/wowchemy-hugo-themes/releases)

## Relevant Links

- [Easily make an academic CV website to get more cites and grow your audience 🚀](https://wowchemy.com/blog/easily-make-academic-website/)
- [What&#39;s new in v5.2?](https://wowchemy.com/blog/whats-new-in-v5.2/)
- [What&#39;s new in v5.1?](https://wowchemy.com/blog/whats-new-in-v5.1/)
- [Version 5.0 (February 2021)](https://wowchemy.com/blog/version-5.0-february-2021/)
- [Version 5.0 Beta 3 (February 2021)](https://wowchemy.com/blog/version-5.0-beta-3-february-2021/) -->