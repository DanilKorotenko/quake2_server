## How to setup Quake 2 Server on Google Computer Engine

### Create Virtual machine 

### Reserve ip address

### Setup firewall rule

### Connect to vm via SSH

### Install quake2-server
sudo apt install quake2-server

possible it could not find the package, then update apt

sudo apt update
sudo apt upgrade

### Install unzip

### Create archive with game files

### Copy game files to vm

### unzip game files
unzip game-files-archive

### install game files
game-data-packager -i quake2 game-files-folder

possible it create a package but fail on install, then
install the package manually

sudo apt install sudo apt install ./quake2-full-data_64_all.deb

### 

You can use the [editor on GitHub](https://github.com/DanilKorotenko/quake2_server/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/DanilKorotenko/quake2_server/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
