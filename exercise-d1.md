
-- Exercise
1. Init a git repo named streaming-app ( bare repo )
```
mkdir streaming-app
git init
```
2. Add a Readme.md file and commit with message "Readme file added"
```
echo "#my readme" >> README.md  # we can do touch README.md as well
git add README.md
git commit -m "Readme file added"
```
3. Add another file "License.md" and commit with message "License file added"
```
echo "#my readme" >> LICENSE.md  # we can do touch README.md as well
git add LICENSE.md
git commit -m "LICENSE file added"
```
4. add line "# Streaming app to see videos" in README.md file and commit with message "Header added"
```
echo "# Streaming app to see videos" >> README.md
git add README.md
git commit -m "Header added"
```
5. Add line "## video 1 added" to README.md file and run "git diff" command to identify changes
```
echo  "## video 1 added" >> README.md
git diff

``
6. Stage the changes in README.md file and commit.
```
git add README.md
git diff # should show nothing
git diff --staged # shows diff from modified + staged files
```
7. Add line "Copyright: Syeda" to license.md and README.md file both. Staged README.md file only and commit. Do the same for License.md file.

```
echo  "Copyright: Syeda" >> README.md
echo  "Copyright: Syeda" >> LICENSE.md
git add README.md
git status
git add LICENSE.md
git status
git commit -m "copyright added"
```