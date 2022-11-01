# Host Resume as Markdown format File.
## Purpose
--------------------
- The purpose of this Project is to introduce users with specific steps of creating resume on markdown. This project will also include some of the key principles that are mentioned in *Andrew Etter's Book Modern Technical Writing.* Link to the book can be found under "More Resources".

## Prerequisites
--------------------
Three components are required to host our resume as markdown file on github with the help of jekyll.

- Resume Standards
    - To create a resume in markdown format we first require a formatted resume that meets [University Of Manitoba career services standards](https://umanitoba.ca/student/careerservices/media/Resume.pdf).
- Markdown tool
    - I have been using VSCODE to create and edit my markdown due to my past experience with vscode tools and interface. But feel free to use any editors of your choice. [Here](https://www.oberlo.ca/blog/markdown-editors) are the top most editors that can be useful for beginners. I highly recommend first time users to check out "More resources" for one of the best markdown tutorials.
- Github Pages
    - Github is an online distributed platform that lets users store and share their repositories on cloud with zero cost. You are required to have a github account for this project therefore click [here](https://github.com) to sign up.

## Instructions
--------------------
### Github pages
1. Create new repository
    - Go to [Github Login Page](https://github.com/login) to login or sign up.
    - Locate **NEW** button to create new repositories on the left section of the page and click on it.
    - Fill out *Repository Name* as ``[your-github-name].github.io``
    - Adding `description` is optional.
    - Make sure repository is set to `public`.
    - `Add a README File` should be unchecked.
    - `Add a .gitignore` template set to **None**.
    - `Choose a license` set to **None**.
2. Adding files into repository
    - One repository has been created locate **`Quick setup`** section.
    - Click on `uploading an existing file` to add files from your local machine.
    - Locate and click on `choose your files`.
    - Upload your resume as`[index.md]` file. **Important: Filename name should be identical**
    - Add description to keep tracks for the future.
    - Do not forget to click `commit changes` button


### Hosting your Website
You can host your website with two different techniques.
1. **Using Ruby and Jekyll**
    - Install Ruby
        - Go to [Ruby website](https://www.ruby-lang.org/en/documentation/installation/) and follow the necessary steps to install ruby according to your specification of local machine (MacOS or Windows).
        - Type in `ruby -v` on your terminal/cmd to confirm the installation of ruby.

    - Install Jekyll
        - Check out the [Quick-start](https://jekyllrb.com/docs/) page for prerequisites/requirements then go to [Jekyll installation page](https://jekyllrb.com/docs/installation/) and follow the necessary steps to install jekyll based on the specification of your local machine.
        - Type in `jekyll -v` on your terminal/cmd to confirm the installation of ruby.

    - Create static website
        - Locate and open terminal on your machine.
        - Open the folder in which your resume and readme files are saved in
        - Run command on terminal `jekyll new [your-github-name].github.io`
        - After locate 

    - Making a static website
        - Navigate to `settings` in your `[your-github-name].github.io` repository.
        - Jekyll has created the website in our local machine
        - Run `bundle exec jekyll build` to execute the new website.

    - Customize 
        - Locate **_posts** folder in your `[your-github-name].github.io` folder.
        - Follow this format `YYYY-MM-DD-resume.md` to add date in the front of resume file name.
        - 

2. **Using Github static website using index.md**
    - Go to your preferred browser and type in `https://[your-github-name].github.io`
        - You will successfully be able to open the website.
    - Customize theme
        - Browse to `settings` in your github page repository where your files are located.
        - On the left in the index section of the page click on `Pages`
        - Locate the button `add a jekyll theme` link on the page.
        - Follow the necessary steps shown in Adding a theme section in [documentation](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll)



### More Resources
- [Markdown]()
- Git can be challenging at first. I highly recommend using [this]() Tutorial to get use to the commands and interface.
- [Modern Technical Writing](https://www.goodreads.com/en/book/show/28433138-modern-technical-writing)



## Authors and Acknowledgments
--------------------
- Etter
- Group member: 
- Group member: 
- Group member:


## FAQs
--------------------
1. Why is Markdown better than a word processor?
    > Using markdown is very simple and efficient. Simple in the sense that you are not required to learn multiple features to fully use the markdown editors compared to microsoft word or any other editors. Furthermore markdown file gives you an extra level of flexibility as you can use [Pandoc](https://pandoc.org/MANUAL.html) to convert from .md to any other formats (Few popular formats: .html, .pdf, .latex, .docx with 25+ other formats)
2. Why is my resume not showing up?
    > 

