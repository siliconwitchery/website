# Silicon Witchery Website

Built with Jekyll and hosted on GitHub pages.

## Setup for local development

1. Set up Ruby environment:

    ```sh
    brew install rbenv
    rbenv init
    rbenv install 3.3.4
    rbenv local 3.3.4
    ```

1. Restart your shell.
2. 
1. Install dependencies:

    ```sh
    bundle update
    ```

1. Run:

    ```sh
    bundle exec jekyll serve --livereload --open-url
    ```
