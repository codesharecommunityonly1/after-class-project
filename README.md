# push command
git add.
git commit -m "first commit"
git push origin main

#🟡 Option 2: Use Git Large File Storage (Best for videos)

If you actually need the video in repo:

git lfs install
git lfs track "*.mp4"
git add .gitattributes
git add project4/video.mp4
git commit -m "Add video using Git LFS"
git push origin main