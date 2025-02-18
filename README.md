# Contributor guidelines for the MIMI project

Welcome to the GitHub contributor guidelines for MIMI. This documentation will outline some basic principles and best practices to follow when using GitHub to make contributions to MIMI. 

These guidelines assume that you have some prior experience of using GitHub, therefore if you are completely new to GitHub, it's recommended that you read the following [introductory documentation](https://docs.github.com/en/get-started/start-your-journey) and access this [introductory course](https://skills.github.com/).

Whilst every effort has been made to ensure that these guidelines are as detailed as possible, it's likely that some aspects of contributing are not covered. Therefore if you do have any questions, please discuss with one of us, or email us at [HQ.MIMIGitHub@wfp.org](HQ.MIMIGitHub@wfp.org).

### Creating a new repository

For each MIMI data or coding project, a GitHub repository is recommended to store and manage your code. If you are an internal team member, you will need to login to the MIMI-wfp account to get a repository set up. Once you are logged in, click on the "Repositories" tab, and then click "New". Give your repository a suitable and self-explanatory name, and decide if you would like your repository to be private or public. We recommended that you initialise your repository with a README file, a .gitignore and a GNU General Public License v3.0. Finally, click "Create repository" to complete the process.

If you are an external collaborator, you won't have access to the MIMI-wfp account. Therefore, please discuss with your MIMI focal point, or email us at [HQ.MIMIGitHub@wfp.org](HQ.MIMIGitHub@wfp.org) to get a repository set up.


### Managing access

Next, you will need to give access permissions to any collaborators who will require access to the repository. To do this, you will need to open the "Settings" tab of your repository. In the left-hand panel, click "Collaborators", and then "Add people" as shown in the image below:

![github_contributor](https://github.com/user-attachments/assets/ac305d25-2759-4f1e-a0dd-59618e3426ab)

The collaborators you have invited will now have full access to the repository, and will therefore be able to pull (read) the contents of the repository, and push (write) changes to the repository. They will also be able to perform other actions such as cloning and forking repositories, or creating branches.

If you are an external collaborator and require access to a repository, please discuss with your MIMI focal point, or email us at [HQ.MIMIGitHub@wfp.org](HQ.MIMIGitHub@wfp.org).


### Cloning a repository

So that you can start working on a project from your computer, it is helpful to clone the repository to your local machine or cloud hosted development environment. To do so, please follow the these [instructions](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository). 

If you would rather use a GUI instead of the command line, use the GitHub Desktop app and follow these [instructions](https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop).


### Branches

We would recommend that the main branch in your repository should only contain finalised and clean code, therefore avoid committing changes directly to the main branch. Instead, we recommend creating a new branch for any code that is a work in progress, and agreeing a naming convention for branches with your co-collaborators. (You can learn more about branches [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches))

Once you are happy that the code in your branch is ready to be merged into the main branch, you can then submit a pull request.

### Submitting pull requests

To start a pull request. Firstly "push" the branch that you have been working on. Now go to the MIMI GitHub repository, you should see your branch appear at the top of the page next to a green button labelled "Compare & pull request".

<p align="center">
<img width="700" alt="Submit a pull request" src="https://github.com/kmtang/MIMI/assets/90572354/3790d37e-21ff-4126-aa3b-44609b028937">
</p>

Click this button, and you will be taken to a page where you can "open a pull request". Here you'll be asked to add a title and description for your pull request. You will also be given the opportunity to "Request a review". You should do this whenever you are making contributions to a project that somebody else is working on, by requesting a review from that person, they will be given an opportunity to review the changes and contributions that you have made before merging them into the main branch.

If you have request a review from someone, please make sure that you inform them that you are doing so.

![Screenshot 2024-03-29 at 12 59 27](https://github.com/kmtang/MIMI/assets/90572354/a949bc29-ab41-45f5-a000-7821cd04fd72)

Once you are happy with everything, click "Create pull request"

### Merging pull requests

If you are the sole contributor to the project you have submitted the pull request for, you can go ahead and merge your own pull request (and resolve any merge conflicts that may have arisen). However, if you have requested a review, you will need to wait for the reviewer to approve the pull request and perform the merge.

If you are a reviewer, you will find your review requests in the "pull requests" tab in the repository. Click on the request, and click "add your review".

<p align="center">
<img width="850" alt="Merge pull request" src="https://github.com/kmtang/MIMI/assets/90572354/edb614d9-d047-4c6f-9716-f48311f3c01d">
</p>
<br>
You will then be taken to a page where you are able to review the changes made. If you are happy with the changes made, you can click "Approve" and "Submit review". Otherwise you can submit feedback or request changes from your collaborator as required.

![code_review](https://github.com/kmtang/MIMI/assets/90572354/dfc752dc-3745-4b27-b64b-4294023d5a40)

If any merge conflicts do arise, it is advised that you arrange a meeting or short video call to resolve conflicts with your collaborator (unless the conflicts are due to inconsequential differences such as comments or empty lines, in which case you can resolve these yourself).

Once all changes are approved, you may now merge the pull request into the main branch!

![merge](https://github.com/kmtang/MIMI/assets/90572354/7b31efca-f708-48fb-a3a9-04dcc1bf20b4)

If you would like to learn more about pull requests, please read the following [documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).

### Summary

These guidelines have outlined a standardised workflow for contributing to the MIMI repository. By following these guidelines, we can ensure that our repository remains tidy and functional, whilst also ensuring that collaboration with other team members is as smooth and streamlined as possible.

If you have any suggestions for how we can improve our workflow, we would love to hear them! Thank you for your contributions! 

