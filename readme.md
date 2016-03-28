# git goals!

A really simple utility for tracking things like commit size (only commit size now) in the git log for a user.

If you are me (Daniel Sellers) and you want the commit size limit to be 300 lines... then you can just run `git-goals`. If not then you want to run `git-goals 'Your Git Author Name' number-of-lines`

To install this wonder: `npm install -g git-goals`

It also now outputs the number of reviews done vs the number of commits created. This works well with gerrit... and probably not super well with other things.
