# hugo-example

## What is this?

This is an example site for [Hugo book theme](https://github.com/alex-shpak/hugo-book).

## Things I've tried

- [ ] Installing Hugo
    ```shell
    brew install hugo
    ```
- [ ] Installing hugo-book (as a Hugo module)[https://github.com/alex-shpak/hugo-book/tree/master?tab=readme-ov-file#installation]
    ```shell
    hugo mod init github.com/repo/path
    ```
- [ ] Configuring hugo-book
    - [ ] Adding settings from config.toml to hugo.toml
    - [ ] Automatic generation of the left-side menu
        - I set `/docs` as the root directory for Hugo and want to automatically generate from `/docs/content`, so I set `BookSection` to `/`
    - [ ] Overriding the left-side menu
        - By default, it is automatically generated from the `docs` directory