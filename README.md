git checkout -b my-feature

echo "Is this a feature?" \
    | tee something.txt

git add .

git commit -m "My feature"

git push --set-upstream origin my-feature

cat Dockerfile

cat .github/workflows/pr.yaml

##########################
# Running GitHub Actions #
##########################

gh pr create \
    --title "My feature" \
    --body "Read the title"
