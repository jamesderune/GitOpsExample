git checkout -b my-feature

echo "Is this a feature?" \
    | tee something.txt

git add .

git commit -m "My feature"

git push --set-upstream origin my-feature

cat Dockerfile

cat .github/workflows/pr.yaml

# Running GitHub Actions #

Notice you need to install gh for this (gitlab cli) but you can still just use the GUI for this

gh pr create \
    --title "My feature" \
    --body "Read the title"
