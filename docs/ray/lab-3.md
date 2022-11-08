---
id: customizing-03
---

[Go to previous lab section](/ray/lab-2.html)

# Understanding Repository Structures

There are two ways we set up our repositories, flat file and multi-branch repositories.

---

## Multi-branch Repositories
[![CodeSpaces](screenshots/codespaces_branches.png)](https://github.com/LinkedInLearning/hands-on-react-2508422)

For sites that use build processes, like a lot of web projects we use one or two branches for each video in the course. We name our branches according to the chapter and the video number in the course.

So, for example if you find a branch called `01_03`, that branch would correspond to the first chapter and the third video in that chapter.

If you see a `b` at the end of a branch name `01_03b`, then that's how the code looks at the beginning of the video and if you see an `e` (as in `01_03e`) at the end, that's how the branch looked at the end of the video.

---

### Exercise

1. Go to the [hands-on-react](https://github.com/LinkedInLearning/hands-on-react-2508422) repository 
1. Click on the branch popup
1. Look at the branches
1. Switch to the 03_02b branch.
1. Switch to the [src](https://github.com/octocloudlabs/supercharge-customize/tree/03_02b/src) folder.
![03_02b](screenshots/codespace_03-02.png)
1. Now switch to the 03_02e branch.
![03_02e](screenshots/codespace_03-02e.png)
1. Notice that now, there are a few extra CSS files.

**Pro Tip**: Github has a built in diff tool that's part of pull request, but you can use it to compare branches by adding `/compare/BRANCH01..BRANCH02` to the [end of the URL](https://github.com/octocloudlabs/supercharge-customize/compare/03_02b..03_02e). This is useful when you're trying to show students what you're changing between two states.

[![Compare](screenshots/codespaces_compare.png)](https://github.com/octocloudlabs/supercharge-customize/compare/03_02b..03_02e)

---

## Flat File Repositories

[![CodeSpaces](screenshots/codespaces_flatfile.png)](https://github.com/LinkedInLearning/hands-on-javascript-2499547)

With a flat file repository, all the files are in a single branch, and there are folders for each video in our courses. This works great for simple projects and languages where a flat file system makes it easier to navigate through a project.

You can see a sample of one of our [flat file](https://github.com/LinkedInLearning/hands-on-javascript-2499547) course in Hands On: JavaScript.

### Exercise
1. Go to the [hands-on-react](https://github.com/LinkedInLearning/hands-on-javascript-2499547) repository 
1. Look at file list
1. Scroll and open the [02_03b](https://github.com/LinkedInLearning/hands-on-javascript-2499547/tree/main/02_03b) folder

[Go to next lab section](/ray/lab-4.html)