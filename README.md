HW1: git and GitHub
===================

The file [`data/roster.tsv`](data/roster.tsv) is a *tab-separated-values* (TSV)
file, so called because each column is separated by a tab (`\t`) character. Each
row represents a single student; the columns are as follows:

-   GitHub username
-   Email address (ideally, the one that matches up with your CUNYfirst one)
-   (Optional; not mandatory) your preferred pronouns, or blank

Your assignment is to add a row to this file with your information by issuing a
pull request using the fork-and-pull model (see below). Your pull request should otherwise
preserve the integrity of the roster; i.e., it should not delete other students'
entries or add extraneous information.

You *must* make your pull request from a non-master branch of your fork.

Once you see that your pull request has been accepted, you are done with the
assignment.


Fork-and-Pull
-------------
0. From the repository in your web browser....
1. Click on the "Fork" button in the top right. Once this is complete, you will be taken to your
remote fork’s GitHub page.
2. Click on the green "Code" button on the right. This will open a dropdown menu, from which you should select "SSH" and then click on the copy icon to the right of the URL to copy it to your clipboard.
3. In your terminal run `git clone URL-YOU-JUST-COPIED`  (Now you have a fork -- a copy -- of the original repository!)
4. Working from your local fork, create a new branch (not main) with a name of your choosing and make your changes
5. Make your pull request


Hints
-----

-   See more about pull requests here: [`GitHub docs: pull request from a fork`](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork)
-   If you're leaving the third field blank, you should still have a tab after
    the second column. That way, there are three columns on all lines.
-   Make sure you look at the file as it appears on GitHub. If it does not
    appear as you want it to, change it, commit, and push; this second commit
    will automatically become part of your pull request.

