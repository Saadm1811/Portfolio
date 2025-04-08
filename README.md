# Step into your repo
cd your-repo-name

# Delete the old files
rm README.md
rm _config.yml

# Recreate README.md
nano README.md
# (Paste the content I gave earlier)

# Recreate _config.yml
nano _config.yml
# (Paste the updated config version)

# Save and commit changes
git add README.md _config.yml
git commit -m "Recreate README and config file"
git push
