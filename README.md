# Instructions to Use this repo for Guests

First thing, I am very honored to have you for an interview on my blog. Your experience will surely be helpful for our readers to help them grow. We cannot thank you enough for the time you are putting to give this interview and help the community.

This section will thoroughly teach you how to use this repo for answering your interview questions.

### Markdown
We only accept drafts in a MarkDown (.md) file. If you are not familiar with MarkDown files, [here is a great resource to get you started.](http://www.markdowntutorial.com/)

If you aren't a developer and not comfortable with Markdown or Github workflow, no worries :) Just email your concern to viraj@virajkhatavkar.com and I will send you a separate mail with questions. You can answer them inline in your email.

### Step by Step submission:
1. Fork the repo you’ve joined. If you have a fork already, synchronize it with the original version (in case the original was updated with other people’s posts since you forked it)

2. Create a new branch for every guest interview you are invited to write – this is very important. Make sure every new branch is based off of the master branch of your fork. A common error is branching when already on another branch, which will cause your pull requests to be turned into a single pull request if you commit that way. All draft pull requests submitted on the `master` branch will be rejected.

3. There will be a folder matching your name under the Interviews folder. It will be your full name without the local characters.

4. Inside that folder, there will be a draft present in MarkDown format (the file name doesn’t matter as long as it ends in .md) and related images (if you wish to include any in the post).

6. Commit the changes you have made, then push them to your fork on GitHub. Notice that we are pushing the branch we created, not the master:
```sh
git add .
git commit -m "My first interview with Consulting People"
git push origin my-first-interview-with-consulting-people
```

Finally, send a [pull request](https://help.github.com/articles/about-pull-requests/) to the `master` branch.

**When submission is complete:**
Once a draft PR is submitted, it will be given a label of editor-review:

It will then have to be in editor review mode for a specific amount of time until the modifications are completed, and the guest approves the modifications.
