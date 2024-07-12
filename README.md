# Greenwood Community Library Website

Welcome to the Greenwood Community Library website repository! This project aims to enhance the existing website of the Greenwood Community Library by adding new features and improving user experience.

## Overview

This repository documents my contribution to enhancing the Greenwood Community Library website. As a member of the development team, I was tasked with adding content to the website and pushing it to the  GitHub

### Step 1: Understanding the Task and Creating a Repository

The task assigned to our team was to enhance the Greenwood Community Library website by adding a "*"Book Reviews"" section and updating the ""Events"*" page to feature upcoming community events.

I started by creating a repository on Github and named it *"greenwood-library-website"*

I created and added text content to the relevant files on the main branch: *"home.html", *"about_us.html"*, *"events.html"*, *"contact_us.html"**

I staged, committed and pushed the changes to the main branch

### Step 2: Morgan's Contribution: Adding Book Review

Morgan created a branch and named it *"add-book-reviews"*

 git checkout -b add-book-reviews 

Morgan added a new file named *"book_reviews.html"* and input some text content to represent the Book Review section

touch book_reviews.html

After adding the necessary content, he staged the file to prepare it for commit

git add . 

He committed the staged changes along with a descriptive commit message to explain the purpose of the modifications

 git commit -m "Add book reviews section" 

He then pushed the committed changes to the GitHub branch to make them available for review and integration into the main project.

 git push origin add-book-reviews 

### Step 3: Raising Pull Request for Morgan

Morgan navigated to the repository on Github and raised a pull request for the *"add-book-reviews"* branch

The changes were reviewed and the pull request was merged to the main branch.

### Step 4: Jamie's Contribution: Updating Events Page

Jamie created a new branch and named it *"update-events"*

He added a new file and updated the events page with the latest information about upcoming community events.

nano events_page.html 

He staged, commit and pushed changes with a description *"Update to event page"*

### Step 5: Raising Pull Request for Jamie

Before raising a pull request for Jamie's work, a pull request is made from the main branch into Jamie's branch *"update-events"* to ensure it includes any recent changes to the main branch.

 git pull origin main 

It is a crucial step in order to avoid conflicts and to ensure Jamie's work can smoothly integrate into the main project.

Jamie pushed his updated branch to Github 

 git push origin update-events 

Finally, Jamie navigated to the repository on Github, and raised a pull request (PR) for *"update-events"* branch.

It was reviewed and merged into the main branch.

### Conclusion

This collaborative workflow helps in maintaining consistency and avoiding conflicts during the integration of changes made by team members into the main project. It also ensures that changes are thoroughly reviewed and integrated into the project, thereby contributing to the continuous enhancement of the website.
