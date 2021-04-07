# Create Annotated tags: 
git tag -a v1.2 -m "my version 1.4"
# These create tags on your current commit.

# List of tags
git tag

search with -i

git tag -l "v2.0*"
v2.0.1

# view tags data 
git show


# tagging old commits
git log --pretty=oneline
see results, use part of checksum

git tag -a v3.5 a029ac

# Push tags - no happening by default 
git push origin v4.0

# push all tags
git push origin --tags 
