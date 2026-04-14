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


