# The Goat Path Git Lesson
This is the miminum viable git lesson for researchers, also known as the "Goat Path Git." The Oxford definition of goat path is: A (narrow) path or track, especially on a hillside or mountain, such as is made by goats. Here we take a narrow path in describing git that is useful for researchers that need versioning in their day to day professional lives. 

Why a goat path? Well a goat path can be the shortest (and possibly the safest) path to follow in a remote place you're not familiar with (exactly how researchers learning code often feel about versioning technologies). The beauty of a goat path is that something (quite possibly actual goats) have followed that path so many times it's actually cut a path through the vegetation. If it wasn't safe it's very likely the path wouldn't get cut because those things wouldn't be able to retread their path.

In case you've never seen a goat path before: this is one.

<img src="/images/goat_path.jpg" width="450">

If you don't follow the goat path as a beginner, bad things happen sometimes. This is so common with git that the popular comic XKCD has even commented on it.

<img src="/images/git_xkcd.png" width="450">
[Comic by XKCD](https://xkcd.com/1597/)


***Please note:*** there has been no mention of coding above. That's on purpose; git can be used to version regular text (manuscripts, dissertations, theses, etc), data (though there are many, many other [probably better] ways to do this), as well as code! Versioning is great. And versioning is really the whole point here. Git just happens to be the tool we use (but there are many other options, go explore!). 

We've all had this happen before. Researchers do this to version things all the time. There's a better way!

<img src="/images/phd101212s.gif" width="450">
[Comic by Jorge Cham](http://phdcomics.com/comics/archive.php?comicid=1531)


So let's set down some functional requirements for versioning needed by researchers even if they don't know how to code quite yet.

# Functional Requirements

1. Versioning with (fairly) simple tools to track changes in documents, code, data, etc. 
- Give researchers something useful first that allows them to accomplish tasks.
- Let them grow into using other aspects of the tool to solve other versioning needs that will arise as they work with the tool over time.

This is a hammer that you can drive a nail and accomplish a task at nearly any skill level.

<img src="/images/claw_hammer.jpg" width="450">

This is what git gives you out of the box. Each of those tools are probably very useful, but it's so confusing as to be useless until you know how to use each and every one of those attachments. We ain't using this hammer here. Because it's confusing. And confusing is worthless for beginners needing to get something done.

<img src="/images/swiss_army_hammer.jpg" width="450">

2. Researchers need a way to publish what they are working on, collaborate with others to improve code they use, and ultimately make it available to the *entire* world so that others can use it, build on it, repeat it, and many other things to increase human knowledge. Underline collaborate in your mind. Go on meow, underline it.

# The Goat Path

## Gitting Setup on a Computer (get it?)
Be sure that git is installed on the computer. Details found on Google.
1. Create a repository on GitHub
2. Copy URL for the repository
3. `git clone URL` in a directory on whatever computer we're using so we can work with the repo.
4. Now we're all set on the machine you're working on. From here on out it's a cycle. 

## The Goat Path Git Cycle
1. Do some things with the repository (e.g. change code, update the files inside, move things around, etc).
2. `git status` to assess changes to the repository.
3. `git add filename` stage changes for a commit. If you're 100% sure you like all the changes in a repo you can use `git add *` to stage (most) every change.
4. `git status` again. This will show you what you're getting ready to commit. This is super useful!
5. `git commit -m "add a useful message for later here about your checkpoint commit"` to finalize the changes as a commit. This is now a single checkpoint you can always get back to (on the computer you're working on only!).
6. `git push` to GitHub to save your commit out on the web where you can get at it later on some other computer. Also your collaborators can find it there too (and the entire world if it's public!).
7. Start the cycle over again with changing things in the repo (step 1 in the Goat Path Git Cycle).


# Compendium of Git Functions Used
- git clone
- git status
- git add
- git commit
- git push

# Frequently Asked Question
## Where can I go to find more training for Git after these intro lessons?
Great question. If you're at the University of Arizona there are organizations that can help: Research Bazaar Arizona.

# Frequently "Asked" Questions

## I really don't like what you're doing here. If you don't teach researchers $X git function, they're not going to be able to do $"cool thing"/$"survive"/$"be amazing".
Research has been happening for hundreds of years before versioning tools. I think they'll be fine. I'm just trying to teach them something that'll make their life a bit easier.

## You're playing with forces you can't possibly understand!
You're right. I'm a researcher; I do that every day. 
