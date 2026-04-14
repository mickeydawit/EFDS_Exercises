git init
echo "# EFDS_Exercises" > README.md
git add README.md
git commit -m "Add README"
git branch -M main
git remote add origin https://github.com/mickeydawit/EFDS_Exercises.git
git push -u origin main

git clone  https://github.com/mickeydawit/EFDS_Exercises.git
cd <EFDS_Exercises>
# open README.md in an editor, add text, save
git add README.md
git commit -m "Update README with collaborator changes"
git push origin main

git pull origin main
# make edits
git add .
git commit -m 
git push origin main

# Jupyter
.ipynb_checkpoints/
*.pyc
__pycache__/
.env
.venv

echo ".ipynb_checkpoints/" >> .gitignore
git add .gitignore
git commit -m "Add .gitignore"
git push origin main

venv/

git checkout -b feature/notes
# edit, add, commit
git push origin feature/notes
# open a Pull Request on GitHub to merge





