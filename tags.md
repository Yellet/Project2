# ------------ Tagging/versioning the Dashboard ------------

We will use this format, more or less (semantic versioning): 

v1.0.0  (vMajor.Minor.Patch)

- MAJOR when breaking backward compatibility,
- MINOR when adding a new feature which doesn’t break compatibility,
- PATCH when fixing a bug without breaking compatibility

# ------------ Git essential tag commands ------------
# Created and assign tag
git tag -a v1.0.0 -m "Stable version v1.0.0" a029ac
# Push tag to remote: 
git push origin v1.0.0





# ------------ Git more tag commands ------------
# Create Annotated tags: (these create tags on your current commit.)
git tag -a v1.2 -m "my version 1.4"

# List of tags
git tag

Search:
git tag -l "v2.0*"
v2.0.1

# view tags data 
git show
git show v1.0

# tagging specific commits
git log --pretty=oneline
see results, use part of checksum

git tag -a v3.5 a029ac
or
git tag -a v1.0 -m "Stable version v1.0" a029ac

# Push tags - not happening by default 
git push origin v4.0

# push all tags
git push origin --tags 

# youtube tuto:
https://www.youtube.com/watch?v=govmXpDGLpo