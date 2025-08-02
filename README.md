# No Docker Required: Understanding Containers the Linux Way  

The book can also be accessed through [a static website](https://interwebshack.github.io/no-docker-required).

## Build the Book
```bash
poetry run jupyter-book build no_docker_required/ --path-output docs --builder html
```
Output will go to the `docs` folder. You can preview with:
```bash
cd docs
poetry run python -m http.server
```
## Keep `docs/` tracked in Git:  

Because we are publishing to GitHub pages we need to make sure we commit the `docs` folder and merge it into the main branch.  

```bash
git add docs/
git commit -m "Add initial HTML build for GitHub Pages"
git push
```
Then:
1. Go to **Settings > Pages**  
2. Choose:  
  * **Source**: `Deploy from a branch`
  * **Branch**: `main`  
  * **Folder**: `/docs`  
3. GitHub will serve your site from:  
  `https://interwebshack.github.io/no-docker-required`  


## Getting Setup
I like the font size and structure of this  
https://aquaulb.github.io/book_solving_pde_mooc/solving_pde_mooc/notebooks/01_Introduction/01_00_Preface.html  

This example has different format than others - may warrant some review  
https://python-advanced.quantecon.org/intro.html  

Good text Tips and Notes  
https://py-pkgs.org/  

More examples  
https://executablebooks.org/en/latest/gallery/  
