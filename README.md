# AnneWebsite
Documents for personal website

On branch gh-pages, I keep my most recent CV in .docx.
In addition, I store all documents that I want to link to my personal website
as pdfs inside the folder papers. 
If no longer needed, move pdfs to folder archive (inside .gitignore).

To add, remove or update documents, follow these steps:

Steps:

1. open GitBash and cd to the repository AnneWebsite: cd /h/AnneWebsite
note: you should be on branch gh-pages, else: git checkout gh-pages
2. git pull origin gh-pages
3. update the documents as desired e.g. store new pdf in folder papers
4. git add papers
5. git commit -m "which paper was added and date"
note: if you also update CV.docx, also git add and git commit this
6. git push origin gh-pages

To link from the Website to a pdf, use the following url:
https://annekatrinschrenker.github.io/AnneWebsite/papers/filename.pdf

More notes:
1. to get back to main branch: git checkout master
2. the correct README is inside the gh-pages branch, always update there

