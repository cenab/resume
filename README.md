### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex cenab_batu_bora_resume.tex
```
### License

Format is MIT but all the data is owned by Sourabh Bajaj.
The file is edited by Cenab Batu Bora.
