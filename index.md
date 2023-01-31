# Advanced Github

## Git Basics

- What is Git?
Git is a commonly used version control system for various types of developers.

- Why use Git? What problem does it slove?
The same reason you would use any version control, management, sharing, and updating of various projects in terms of the changes made.

- What is the difference between Git and Github?
Git is the tool, Github is where the repositories are stored

## Git Rebase

- What is Git rebase?
Git allows for the movement of and combining of a git branch into a new base.

- What are some advantages and disadvantages of Git rebase? (At least 2 of each)
Git rebase can help you merge the changes of branches similar to a git merge, and  and often leads to a much cleaner product history. However, it also gets rid of the previous branch and is therefore destructive, and it can lead to really long branches in the tree

- When shouldn't you use Git rebase? Why?
I suppose when a get merge will do, because they basically do the same thing except rebase gets rid of the previous branch

Create a new repo and demonstrate your knowledge of the following items with screenshots:

- A rebase merge

- An interactive rebase merge

- When you shouldn't rebase with a remote repo.

## Git reset, checkout, and revert

- What is Git reset?
In a way, its an undo command to a previous commit in the repository.

- What is the difference between hard, mixed and soft?
Hard is a complete reset which gets rid of the commits entirely, Mixed is a basic git reset which sends it back to the working directory, and soft unstages your changes from the last commits

- What is Git checkout?
Git checkout allows you to go to a certain commit in the chain and/or a different branch in the chain

- What is Git revert?
In a way, a safer option than git reset as it actually creates a new commmit that has all the changes undone.

- In what ways are these commands the same and what ways are they different?
They all use the terminal and allow you to travel the tree, that's all that I can think of in terms of same.
Checkout doesn't actually change anything just helps with navigation, git reset is destructive, and git revert creates a new commit that has the changes undone

- When would you use reset, checkout, or revert? Why?
Reset: When you want to entirely erase a change, Revert: When you simply need to fix a change, and Checkout: For Navigation
One could almost equivalate the Reset to: Delete whilst the revert is simply an undo. And I have no idea why Checkout is in this section as it does not change the tree and is simply used for navigation

- ![A Git Reset](Screenshot (446).png)

- ![A Git Checkout](Screenshot (444).png)

- ![A Git Commit](Screenshot (443).png)

- ![A Git Revert](Screenshot (445).png)

## Git Submodules

- What are Git submodules?
A record that points to a specific commit in the tree

- When would you use a submodule?
For use in more complex projects

- What are the advantages and disadvantages of Git submodules?
Advantages: Better organization in larger projects, Better adding and management of commits to certain functions
Disadvantages: Complexity and loss of ease of navigation if in the wrong module.
