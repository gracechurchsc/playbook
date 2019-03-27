# Grace Church Web Volunteer Playbook

## What do I need to know to help?

If you would like to help us update our website with content please contact us to get a login to the CMS and access to the training videos at
communications@gracechurchsc.org. We regularly have needs for everything from content creation and data entry to reviewing transcripts for
inaccuracies (tedious but important!).

If you are looking to help with a code contribution our project uses python, django, wagtail, and postgres. We keep track of changes to the code
with Git and manage our projects with Basecamp. You can review the [Basecamp Todos](https://3.basecamp.com/3097746/buckets/1810537/todosets/280777989) 
to get an idea of how you can help.

If you are interested in making a code contribution and would like to learn
more about the technologies that we use, check out the list below.

   - [Learn Git with Git Immersion](http://gitimmersion.com/)
   - [Learn Python3](https://www.codecademy.com/learn/learn-python-3) (or [Free Python2 Class](https://www.codecademy.com/learn/learn-python>))
   - [Pipenv Guide](https://realpython.com/pipenv-guide/)
   - [Django for Beginners](https://djangoforbeginners.com/) and [Django Tutorial](https://tutorial.djangogirls.org/en/)
   - [Wagtail Tutorials](https://www.accordbox.com/blog/wagtail-tutorials/)
   - [Two Scoops of Django](https://www.amazon.com/Two-Scoops-Django-1-11-Practices/dp/0692915729/ref=sr_1_fkmrnull_1)

## How do I make a contribution?

Never made an open source contribution before? Wondering how contributions
work in our project? Here's a quick rundown!

   1. Get a basecamp login by emailing us at
   communications@gracechurchsc.org. We'll also connect you with a Jump In
   Developer (one of our friendly developers) who can help you setup your
   machine and answer questions. Your Jump In Dev will be your goto person for
   help.
   2. If you haven't done django development before you will need to setup
   your machine to do so. We have a handy guide that your Jump In Developer
   will share with you. Or you can attend one of our Installation Parties.
   3. Find an issue in basecamp that you are interested in addressing or a
   feature that you would like to add.
   4. Clone the repository associated with the issue to your personal
   Bitbucket account. This means that you will have a copy of the repository
   under your-bitbucket-username/repository-name.
   5. Clone the repository to your local machine using `git clone https://bitbucket.com/bitbucket-username/repository-name.git`.
   6. Create a new branch for your fix using `git checkout -b branch-name-here`.
   7. Make the appropriate changes for the issue you are trying to address or the feature that you want to add.
   8. Use `git add insert-paths-of-changed-files-here` to add the file contents of the changed files to the "snapshot" git uses to manage the state of the project, also known as the index.
   9. Use `git commit -m "Insert a short message of the changes made here"` to store the contents of the index with a descriptive message.
   10. Push the changes to the remote repository using `git push origin branch-name-here`.
   11. Submit a pull request from your repository to ours.
   12. Title the pull request with a short description of the changes made and the issue or bug number associated with your change. For example, you can title an issue like so "Added more log outputting to resolve #4352".
   13. In the description of the pull request, explain the changes that you made, any issues you think exist with the pull request you made, and any questions you have for a Grace Developer. It's OK if your pull request is not perfect (no pull request is), the reviewer will be able to help you fix any problems and improve it!
   14. Wait for the pull request to be reviewed by a Grace Developer.
   15. Make changes to the pull request if the reviewing Grace Developer recommends them.
   16. Celebrate your success after your pull request is merged!

## Where can I go for help?

If you need help, you can ask questions in basecamp or chat directly with
your Jump In Developer. We value your help and realize contributing to a
large project like ours is hard. So please don't hesitate to ask for help!

What does the Code of Conduct mean for me?

Our Code of Conduct means that you are responsible for treating everyone on
the project with respect and courtesy regardless of their identity. If you
are the victim of any inappropriate behavior or comments as described in
our Code of Conduct, we are here for you and will do the best to ensure
that the abuser is reprimanded appropriately, per our code.