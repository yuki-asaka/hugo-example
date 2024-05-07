# hugo-example

## What is this?

This is an example site for [Hugo book theme](https://github.com/alex-shpak/hugo-book).

## Things I've tried

- [x] Installing Hugo
    ```shell
    brew install hugo
    ```
- [x] Installing hugo-book [as a Hugo module](https://github.com/alex-shpak/hugo-book/tree/master?tab=readme-ov-file#installation)
    ```shell
    hugo new site docs
    cd docs
    hugo mod init github.com/repo/path
    ```
- [x] Configuring hugo-book
    - [x] Adding settings from config.toml to hugo.toml
    - [x] Automatic generation of the left-side menu
        - I set `/docs` as the root directory for Hugo and want to automatically generate from `/docs/content`, so I set `BookSection` to `/`
    - [x] Overriding the left-side menu
        - By default, it is automatically generated from the `docs` directory
- [x] Configure Github Actions
    - [x] Set up a workflow to deploy to Github Pages
      - no need to set up a Github Apps integration 
