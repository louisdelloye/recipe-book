# recipe-book
Recipe book from my family

## To compile
/!\ WARNING /!\ : requires pandoc to convert md to tex
### Concatenate all markdown files into one
```bash cat recipes/*.md > combined_recipes.md```

### Convert markdown to tex
```bash pandoc combined_recipes.md -o combined_recipes.tex```

### Compile tex to pdf with VSC
or use the following command
```bash pdflatex combined_recipes.tex```