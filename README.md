brew install gh
gh auth login
git push -u origin blackboxai/capture-faces-script
gh pr create --base main --head blackboxai/capture-faces-script --title "Add face capture script (capture_faces.py)" --body "Captures face images to dataset/<name>/ and rebuilds encodings.pkl."
