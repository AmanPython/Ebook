## [Install Pandoc in Windows](https://www.thepolyglotdeveloper.com/2019/10/creating-ebook-pandoc-markdown/)




## Command to Create Epub Using Pandoc

```shell
pandoc -o dist/book.epub metadata.txt *.md --css styles.css --table-of-contents
```