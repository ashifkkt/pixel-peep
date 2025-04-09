# Pixel Peep
Find the original images from the duplicated and variotion images

Perfect! Here’s the revised Pixel Peep GitHub Submission Guide, now updated to include the fork-based workflow, and highlighting that only winners’ code will be merged into the main WeCode organization repository.

📸 Pixel Peep – GitHub Submission Guide

Welcome to the official repository for Pixel Peep, a WeCode Community Project!
This guide will walk you through forking the repo, creating a branch, and submitting your solution using GitHub best practices.

	🔥 Top submissions will be selected, and only the winners’ code will be merged into the main Pixel Peep repository under the WeCode organization!

🚀 Step 1: Set Up Git & GitHub

✅ 1. Install Git

Download and install Git from the official site:
👉 https://git-scm.com/downloads

✅ 2. Create a GitHub Account

If you don’t have one already:
👉 https://github.com

🍴 Step 2: Fork the Repository
	1.	Visit the official repo:
👉 https://github.com/WeCode-Community-Dev/pixel-peep
	2.	Click the “Fork” button on the top-right corner to create a copy under your GitHub account.

📥 Step 3: Clone Your Fork

Now, clone your own forked repository:

git clone https://github.com/your-username/pixel-peep.git
cd pixel-peep

Replace your-username with your actual GitHub username.

🌿 Step 4: Create a Branch with Your Name

In your local repo, create a new branch under your name:

git checkout -b your-name-branch

Example:

git checkout -b anjali-pixelpeep

🔄 Step 5: Sync with Original Repository (Optional but Recommended)

To keep your fork updated with the latest changes:

git remote add upstream https://github.com/WeCode-Community-Dev/pixel-peep.git
git fetch upstream
git merge upstream/main

✏️ Step 6: Add Your Solution
	1.	Navigate to the appropriate challenge folder.
	2.	Upload only the relevant solution file.
	3.	File naming format:
	•	<problem-name>.<ext> → e.g., detect-duplicate.py, detect-duplicate.java

Example Folder Structure:

pixel-peep/
│-- Challenge-1/
│   └── detect-duplicate.py
│-- Challenge-2/
│   └── match-hash.cpp

📤 Step 7: Commit & Push Your Code

Add your file(s):

git add Challenge-1/detect-duplicate.py

Commit with a meaningful message:

git commit -m "Added solution for Detect Duplicate"

Push to your branch:

git push origin your-name-branch

🔁 Step 8: Create a Pull Request
	1.	Go to your forked repo on GitHub.
	2.	You’ll see a “Compare & pull request” option.
	3.	Select your branch and make sure you’re comparing it with the main branch of the original WeCode repo.
	4.	Add a clear title and brief description.
	5.	Click “Create pull request”.

🏆 Winner’s Code Will Be Merged!

✅ The best, original, and correctly working solutions will be selected and merged into the main Pixel Peep repository under the WeCode organization.

So make sure your code:
	•	Works perfectly
	•	Is clean and well-documented
	•	Follows naming and folder structure conventions

⚠️ Important Guidelines

✅ Fork the repo first – do not push directly to the original repo
✅ Always work in your own branch
✅ Upload only the necessary solution file(s)
✅ Use clear and meaningful commit messages
✅ Submit a pull request only from your fork
✅ Keep your fork updated with changes from the original repo

💬 Need Help?

Reach out to us via the WeCode Community Discord or forums.

Happy Peeping! 👀
Let your code stand out — only the best get merged! 🌟
