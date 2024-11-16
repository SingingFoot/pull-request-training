# pull-request-training

# Step 1: Set Up a Repository

Create a New Repository:

Go to your GitHub account.
Click on New to create a repository.
Give it a name (e.g., pull-request-training) and choose visibility (public or private).
Initialize it with a README file for simplicity.
Clone the Repository Locally:

Open a terminal and run:
bash
Copy code
git clone https://github.com/your-username/pull-request-training.git
Replace your-username with your GitHub username.
Navigate to the Repository Folder:

bash
Copy code
cd pull-request-training

# Step 2: Create a New Branch
Create and Switch to a New Branch:

Run:
bash
Copy code
git checkout -b my-feature-branch
Replace my-feature-branch with the name of your branch.
Make Some Changes:

Edit the README.md or add new files.
Save your changes.
Stage and Commit the Changes:

Run:
bash
Copy code
git add .
git commit -m "Added my changes"
Push the Changes:

Run:
bash
Copy code
git push origin my-feature-branch

# Step 3: Create a Pull Request

Go to GitHub:

Open your repository on GitHub.
You should see a notification about your newly pushed branch with an option to "Compare & Pull Request."
Create the Pull Request:

Click on the "Compare & Pull Request" button.
Add a title and description for your changes.
Click Create Pull Request.
Step 4: Review and Edit the Pull Request
Switch to the main Branch Locally:

Run:
bash
Copy code
git checkout main
Review and Test the PR:

Pull the PR branch locally for testing:
bash
Copy code
git fetch origin my-feature-branch
git checkout my-feature-branch
Test the changes in your development environment.
Comment on the PR:

On GitHub, go to the "Files changed" tab of the PR.
Add inline comments to suggest improvements or ask questions.
Request Changes:

Back in the PR view, click on "Request changes" and describe what needs to be updated.
Step 5: Update the Pull Request
Switch Back to the Feature Branch Locally:

Run:
bash
Copy code
git checkout my-feature-branch
Make Updates and Commit Them:

Edit the files as needed.
Stage and commit your updates:
bash
Copy code
git add .
git commit -m "Addressed review comments"
Push the Changes:

Run:
bash
Copy code
git push origin my-feature-branch
Resolve Comments on GitHub:

Mark comments as resolved, if appropriate.
Step 6: Approve and Merge the Pull Request
Review the Updated PR:

Go to the PR on GitHub.
Confirm that all requested changes are addressed.
Approve the PR:

Click on Approve in the review section.
Merge the PR:

Click Merge pull request, then confirm the merge.
Delete the Branch:

After merging, click the option to delete the branch on GitHub.
Practice Repeating the Cycle
Repeat this cycle for additional branches and PRs to refine your workflow and get comfortable with the process.
