#Assignment 0: Git Pratice
##Wyatt Destabelle

###Article Title: How to Write a Git Commit Message
Link: <https://cbea.ms/git-commit/>

I chose this article on writing good git commit messages, which seemed rather appropriate given the assignment. At first, this topic seems almost pedantic- but very rapidly the author presents a strong argument in favor of improving your git commit messages. By being more intentional, clear and concise with your commit messages, it becomes much easier to browse the commit history using `git log`. Once that is done, tools like `git revert` become more powerful, as you are able to much more easily understand what you are reverting *too*. The author then lays out what they call *"The seven rules of a great Git commit message"*. They are as follows:

1. Seperate subject from body with a blank line
2. Limit subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. use the body to explain *what* and *why* vs. *how*

Some of these rules I followed either naturally or by nature of the software I used. In fact in Github Desktop, some of these conventions are enforced by design (Subject line in particular). Along with that, I naturally followed rule 7, using the body to explain the what and why rather than how. It made sense naturally from my perspective, as the how could be infered by something like `git diff`, whereas the what, and particularly the why, are much harder (sometimes impossible) to infer. However, I found rule 5 both interesting and a completely fresh idea to me. It said to put all commit subject lines in the imperative tense (command tense). The argument is simple and makes sense- for one, it meshes with git's own syntactical conventions; Both merge and revert messages utilize the imperative tense. Additionally, your message will then clearly state what will happen if you revert to this commit.

All in all I found this article insightful and perhaps something I will endeavour to add into my own practice.