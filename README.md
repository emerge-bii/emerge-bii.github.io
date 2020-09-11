# Minimal Mistakes remote theme starter

---

## To run the website locally for testing

(instructions modified from https://github.com/academicpages/academicpages.github.io)

### Before running for the first time:

1. Clone this repository.

2. Make sure that rvm, ruby-dev, ruby-bundler, and nodejs are installed. If you get errors when trying to run the commands below, try updating these packages (especially rvm and bundler) to the latest versions. 
    * Note: If installing RVM for the first time, follow the instructions at https://rvm.io/rvm/install. If installing on Ubuntu, the custom Ubuntu package linked in the instructions may not work; instead, follow the instructions under "Any other system".)

3. Run the following commands to initialize the site configuration:

    ```bundle clean``` (no need to run --force)
    ```bundle install``` (to install ruby dependencies; if you get errors, delete Gemfile.lock and try again)

### Each time running:

1. Run the following to start RVM and thus use the correct Bundler version (substituting your username for [USERNAME], and changing the directory if rvm was installed in another location):

    ```source /home/[USERNAME]/.rvm/scripts/rvm```
    
2. Start the server:

    ```bundle exec jekyll serve```
    
3. The website will be visible at [http://localhost:4000/](http://localhost:4000/).


## Minimal Mistakes remote theme starter (original README)

Click [**Use this template**](https://github.com/mmistakes/mm-github-pages-starter/generate) button above for the quickest method of getting started with the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes).

Contains basic configuration to get you a site with:

- Sample posts.
- Sample top navigation.
- Sample author sidebar with social links.
- Sample footer links.
- Paginated home page.
- Archive pages for posts grouped by year, category, and tag.
- Sample about page.
- Sample 404 page.
- Site wide search.

Replace sample content with your own and [configure as necessary](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
