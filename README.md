# AnneWebsite
Documents for personal website

On branch gh-pages, in folder papers/, I store all pdfs that should be linked
to the website. 

Steps CV:
1. update .docx document, save as CV.docx
2. save as CV.pdf and store in folder papers/, replacing the previous version

Steps other papers:
1. store as pdf directly in folder papers/


Steps Git Bash:
1. open GitBash
2. cd to AnneWebsite (cd /h/AnneWebsite)
3. on each branch (git checkout master OR git checkout gh-pages), do:
a. git status
b. git add papers
c. git commit -m "which new pdf you put there or changed"

Note: To link from the Website to the pdf, use the following url:
https://annekatrinschrenker.github.io/AnneWebsite/papers/filename.pdf
d. git push origin gh-pages OR git push if in master
e. always end in master e.g. git checkout master 
