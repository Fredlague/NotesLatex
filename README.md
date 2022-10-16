# Notes de Cours et Devoirs Latex

## Méthode pour un nouveau cours
- Créer sur GitHub SIGXXXX_Latex
- cd dans SIGXXXX
- Créer LatexFiles
- cd dans LatexFiles
- git init
- git config core.sparseCheckout true
- git remote add -f origin https://github.com/Fredlague/NotesLatex.git
- echo "SIGXXXX_Latex/*" > .git/info/sparse-checkout
- git checkout main
