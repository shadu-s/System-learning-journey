So today is the start of my journey. I started with creating and refining plan...and now i started with

1. `pwd` to know the path,

2\. `ls` to see the list of directories and files
3. `git status` to know the state

when I ran git status first, i faced a problem...git hub didn't trust the folder I started working on...so I had to run

```powershell

git config --global --add safe.directory "F:\\System learning\\systems-visibility-labs"

```

this one makes the git trust the folder and files

then we linked our GitHub

```powershell

git config --global user.name "shadu-s"
git config --global user.email "214380983+shadu-s@users.noreply.github.com"

```

after this i attached this GitHub with my repo...before that I separated my progress from the main plan file...didn't want to add plans

day 1 progress files are on systems-visibility-journey...then we used the command



```powershell

git remote add origin https://github.com/shadu-s/System-learning-journey.git

``` 



this showed a flaw, that GitHub doesn't trust the file...we again ran



```powershell

git config --global --add safe.directory "F:\\System learning\\systems-visibility-journey"

```



that solved the problem..then we ran



```powershell

git remote -v

```



after that



```powershell

git status

git remote add origin https://github.com/shadu-s/System-learning-journey.git

git branch -m main

git push -u origin main

```



well after that we got into the notepad folder and i tried to push this notepad file in the repo but nothing entered the repo...turns out this file wasn't migrated to the journey folder...so we went inside the



`F:\\System learning\\systems-visibility-journey\\notes>notepad .\\notes\\day-01-journal.md`



this one failed as what it does is searched for notes folder again which we already are in...so next time we did this



`F:\\System learning\\systems-visibility-journey\\notes>.\\day-01-journal.md`



this created the file and we just copy pasted the writings in this file..

