# my-ebooks

Download and install the Git command line extension. You only have to set up Git LFS once.<br>

git lfs install<br>
Select the file types you'd like Git LFS to manage (or directly edit your .gitattributes). You can configure additional file extensions at anytime.<br>

git lfs track "*.psd"<br>
Make sure .gitattributes is tracked<br>

git add .gitattributes<br>
There is no step three. Just commit and push to GitHub as you normally would.<br>

git add file.psd <br>
git commit -m "Add design file" <br>
git push origin master <br>
