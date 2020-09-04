# Taking Inventory

Do you know how to use the terminal?  If you don't, [start here](https://www.learnenough.com/command-line-tutorial/basics).

The first step in the installation process is noting what software you have installed. We're running Linux (operating system Ubuntu 18.04) and have Hugo (0.74.3) installed. If you don't have Hugo, follow their [installation instructions](https://gohugo.io/getting-started/installing). With Hugo installed, run `hugo new site best-website` in the terminal.

````
cat /etc/lsb-release
hugo version
hugo new site best-website
````
Image

Know More!
This commands generates a folder structure, and two files. `config.toml` is an important file, it sets variables any page can access.

# Seeing HTML

The first command is running the server, this generates HTML for your web browser to read. Move into the correct directory with `cd best-website` and run `hugo server`.  This generates warnings in the terminal, and you should be able to open a web browser at http://localhost:1313/ 

There is nothing there but an empty HTML page.

# Seeing Home

To make a home page interesting, you have to include your own content. Make a home page layout the fancy way with `echo "<div>Best</div>" > layouts/home.html`. Or be relaxed and make a text file named `home.html` in the `layouts` directory (in the `best-website` directory) and write HTML in there.

Know More!
You could name this file many things. Anything in the [lookup order](https://gohugo.io/templates/lookup-order/#examples-layout-lookup-for-home-page) for a `home` page works.

# Seeing Content

If you stopped and restarted your server with `Ctrl-C`,`hugo server` you could see that we had removed one of the errors. Our home page has a template. 


# Seeing Page

# Seeing Pages
