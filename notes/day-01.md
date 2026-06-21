# Day 1 Notes

Today is the start of my journey.

I started by learning a few basic terminal and Git commands:

1. `pwd` shows the current path.
2. `cd` changes the current folder.
3. `ls` shows the files and folders in the current folder.
4. `git status` shows the state of the Git repository.

When I ran `git status` for the first time, I saw a problem. Git did not trust the folder because the folder owner and my current Windows user were different.

I fixed it with:

```powershell
git config --global --add safe.directory "F:\System learning\systems-visibility-labs"
```

Then Git needed my GitHub name and email before it could make a commit.

I set them with:

```powershell
git config --global user.name "shadu-s"
git config --global user.email "214380983+shadu-s@users.noreply.github.com"
```

What I learned: errors are not just failures. They are messages that explain what the computer needs next.

