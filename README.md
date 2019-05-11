# Build a webslide using jekyll-theme-slides

## Install Ruby + Jekyll

1. Install a full Ruby development environment
2. Install Jekyll and bundler gems
    ```bash
    gem install jekyll bundler
    ```

## Build your slides

1. Clone the slide-jekyll-sample project
    ```bash
    git clone https://github.com/pnhung177/slide-jekyll-sample.git
    ```
2. rename the directory:
    ```bash
    mv slide-jekyll-sample slice-your-project-name
    ```
3. Change current working dir to this project dir
    ```bash
    cd slice-your-project-name
    ```
4. Delete the .git directory locally
    ```bash
    rm -rf .git
    ```
5. Create a new .git repository
    ```bash
    git init
    ```
6. Update the `_config.yml` file, content in current slides
7. Start the jekyll
    ```bash
    jekyll serve
    ```
8. Open webpage `http://0.0.0.0:4000/slide-your-project-name/` in a browser
9. Add more slides, test and update to git repository
    ```bash
    git add .
    git commit -m "... your comment here ..."
    ```
10. Deploy slides that stored in `_site` directory

## References

* [Jekyll Quickstart](https://jekyllrb.com/docs/)
* [jekyll-theme-slides](https://rubygems.org/gems/jekyll-theme-slides)
