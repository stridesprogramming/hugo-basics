# Taking Inventory

Do you know how to use the terminal?  If you don't, [start here](https://www.learnenough.com/command-line-tutorial/basics).

The first step in the installation process is noting what software you have installed. We're running Linux (operating system Ubuntu 18.04) and have Hugo (0.74.3) installed. If you don't have Hugo, follow their [installation instructions](https://gohugo.io/getting-started/installing). With Hugo installed, run `hugo new site best-website` in the terminal.

````
cat /etc/lsb-release
hugo version
hugo new site best-website
````
Image

---
Know More!
This commands generates a folder structure, and two files. `config.toml` is an important file. You can set variables that every page can access here.
---

# Seeing HTML

The first command is running the server, this generates HTML for your web browser to read. Move into the correct directory with `cd best-website` and `hugo server`.  This generates three warnings. 
