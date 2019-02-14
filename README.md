# The Goat Path Git Lesson
This is the miminum viable git lesson for researchers, also known as the "Goat Path Git." The Oxford definition of goat path is: A (narrow) path or track, especially on a hillside or mountain, such as is made by goats. Here we take a narrow path in describing git that is useful for researchers that need versioning in their day to day professional lives. 

*Please note:* there has been no mention of coding here. That's on purpose; git can be used to version regular text (manuscripts, dissertations, theses, etc), data (though there are many, many other [probably better] ways to do this), as well as code! Versioning is great. And versioning is really the whole point here. Git just happens to be the tool we use (but there are many other options, go explore!). 

![PHD Comics About Versioning](~/images/phd101212s.gif?raw=True)

# Functional Requirements

1. Versioning with (fairly) simple tools to track changes in documents, code, data, etc. 
- This removes the all

2. Researchers need a way to publish what they are working on, collaborate with others to improve code they use, and ultimately make it available to the *entire* world so that others can use it, build on it, repeat it, and many other things to increase human knowledge. Underline collaborate in your mind. Go on meow, underline it.

# The Goat Path

## Gitting (get it?) Setup on a Computer
1. Create a repository on GitHub
2. Copy URL for the repository
3. `git clone URL` in a directory on whatever computer we're using so we can work with the repo.
4. Now we're all set on the machine you're working on. From here on out it's a cycle. 

## The Goat Path Git Cycle
1. Do some things with the repository (e.g. change code, update the files inside, move things around, etc).
2. `git status` to assess changes to the repository.
3. `git add filename` stage changes for a commit. If you're 100% sure you like all the changes in a repo you can use `git add *` to stage (most) every change.
4. `git commit -m "add a useful message for later here about your checkpoint commit"` to finalize the changes as a commit. This is now a single checkpoint you can always get back to (on the computer you're working on only!).
5. `git push` to GitHub to save your commit out on the web where you can get at it later on some other computer. Also your collaborators can find it there too (and the entire world if it's public!).
6. Start the cycle over again with changing things in the repo (step 1 in the Goat Path Git Cycle).


# Compendium of Git Functions Used
- git clone
- git status
- git add
- git commit
- git push

# Frequently "Asked" Questions

## I really don't like what you're doing here. . If you don't teach researchers $X, they're not going to be able to do $"cool thing"/$"survive"/

## You're playing with forces you can't possibly understand!
I'm a researcher; I do that every day. But this lesson isn't the end of the road. 


