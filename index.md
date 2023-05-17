<img align="right" width="1000" height="200" src="https://raw.githubusercontent.com/CU-ESIIL/innovation-summit-webpages/main/esiil-earthlab-cires-header.png">



# Part 1: Create your own webpage using GitHub pages

You will: 
* Make a `GitHub` account
* Create a new **repository** in `GitHub`
* Build a **webpage** using `GitHub pages`
* Learn how to use `Markdown` and `HTML`

For this first assignment, you're going to create a **personal webpage** using <a href="https://pages.github.com/" target="_blank">**GitHub pages**</a> and the popular **markup language to format text** <a href="https://www.markdownguide.org/getting-started/" target="_blank">**Markdown**</a>. You'll use this webpage to share some biographical information and a photo of yourself. You can add content from any of your GitHub repositories to build an online portfolio if you'd like. 

> You can read more about `git` and `GitHub` in our open <a href="https://www.earthdatascience.org/courses/intro-to-earth-data-science/git-github/" target="_blank">**Earth Data Science**</a> textbook. 

***

## Step 0: Create a GitHub account
Use <a href="https://github.com/signup" target="_blank">**this link**</a> to create a free GitHub account. _**If you already have a GitHub account, there is no need to create a new account!**_

> **Protip:** Your GitHub <a href="https://happygitwithr.com/github-acct.html" target="_blank">**username**</a> should be short and something that you can easily remember and identify with.

***

## Step 1: Create a new repository

Once you have a GitHub account, get started by creating a new **repository** for your webpage, names `yourusername.github.io`. You can make a webpage out of any repository, the `yourusername.github.io` repository is special - it will show up at `https://yourusername.github.io` instead of `https://yourusername.github.io/repository-name`.

To do this you can:
* Navigate to your profile page
  * Click on the dropdown arrow next to your profile photo in the upper right corner
  * Select **Your profile**

<img src="https://raw.githubusercontent.com/cu-esiil/innovation-summit-webpages/main/images/your-profile.png">
  
Select the **Repositories** tab from the menu near the top of the page.

<img src="https://raw.githubusercontent.com/cu-esiil/innovation-summit-webpages/main/images/repositories.png">


> **NOTE:** A <a href="https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories" target="_blank">**repository**</a> contains all of your project's files and each file's **revision history**. You can discuss and manage your project's work within the repository.


From here, you can select the green **New** button on the right to get started.

<img src="https://raw.githubusercontent.com/cu-esiil/innovation-summit-webpages/main/images/new-repo.png">


Again, we recommend naming your repository `yourusername.github.io`, replacing "yourusername" with your GitHub username.

* You can give your repository a **description**
* Make your repository **Public**
* Check the box to add a `README` file to your repository (you will edit this later using **Markdown**)
* You can skip adding the **gitignore** for now
* Choose a **License** for your repository if you like. (This is more important for code repositories; for websites we are usually more concerned with copywrite.)
* Once you're done, select the green **Create Repository** button at the bottom of the page.

***

## Step 2: Create a new `index.md` file
You will create a new file called `index.md` that will serve as the content for your webpage. To do this you can :
* Select the **Add file** button from the menu on the right
* Select **Create new file**. 

<img src="https://raw.githubusercontent.com/cu-esiil/innovation-summit-webpages/main/images/create-new-file.png">

From here you will create a new **Markdown** file called `index.md` 

Add the following **Markdown header** text to your index file:
`## ADD YOUR NAME HERE` 

>**NOTE:** You can change this text to your name or something else. This is _**your**_ website, and you'll always be able to come back and make edits!

***

## Step 3: Commit changes
Now that you've created your `index.md` file and added some text, you'll want to **commit changes** to your repository. Add an optional extended description of your changes and then select the green **Commit changes** button at the bottom of the page.

<img src="https://raw.githubusercontent.com/cu-esiil/innovation-summit-webpages/main/images/commit-changes.png">

***

## Step 4: Build your webpage
Once you've created your `index.md` file you're ready to build your webpage. From your repository, select the **Settings** tab from the right end of the menu. 

<img src="https://raw.githubusercontent.com/cu-esiil/innovation-summit-webpages/main/images/settings.png">

From here, scroll down the menu on the **left** and select **Pages**.

<img src="https://raw.githubusercontent.com/cu-esiil/innovation-summit-webpages/main/images/pages.png">

Now you'll want to select the **main** option under the **Branch** heading and then select **Save**.

<img src="https://raw.githubusercontent.com/cu-esiil/innovation-summit-webpages/main/images/select-branch-main.png">

***

## Step 5: Check on your webpage
Check in on your webpage to see how it is doing by opening the link **`https://username.github.io/repository-name/`** in a **new tab** in your web browser. Here, you'll need to replace `username` with your GitHub username and `repository-name` with the name of the repository that you created above. Once you see your name (or whatever text you added to your `index.md` file in **Step 2**) appear as a Markdown header, then you know your webpage is working!


> **NOTE:** Sometimes your webpage can take a minute or so to build so _be patient_ and refresh every 30 seconds or so until the page is done building. You can also go to the `Actions` tab on your repository you can see if the build process is done or not.

# Part 2: Use git to edit your webpage off of GitHub

For more information, check out:
  * <a href="https://www.earthdatascience.org/courses/intro-to-earth-data-science/git-github/" target="_blank">The Earthlab textbook on git and GitHub</a>
  * <a href="https://docs.github.com/en/get-started/quickstart/hello-world" target="_blank">GitHub's Quickstart page</a>


## Step 1: **Clone** your repository to JetStream2
First, get the link to your repository:

 1. Return to your repository home page by clicking the `Code` tab
 2. Makeing sure `SSH` is highlighted, click the copy button next to the link

<img src="https://raw.githubusercontent.com/cu-esiil/innovation-summit-webpages/main/images/git-clone-link.png">

Next, log in to JetStream2, and **clone** your repository (make a local copy) using the JupyterHub Git widget.

Alternatively, you can use the following command in the terminal **making sure to replace `<paste-your-link-here>` with your link that you copied**:

```bash
git clone <paste-your-link-here>
```
***

## Step 2: Start adding information to your webpage
Now you're ready to start adding some more information to your webpage. Open the `index.md` file that you just created **on JetStream2**. You will use **Markdown** and **Hypertext Markup Language (HTML)** to add text, links, images, and other content to your webpage. Markdown and HTML are both common markup langauges, and have wide application including formatting text, report writing, and website development.

> **NOTE:** You may want to review the <a href="https://www.markdownguide.org/basic-syntax/" target="_blank">**Markdown Basic Syntax guide**</a> to help you format your webpage using **`Markdown`** and **`HTML`**. We also have a <a href="https://www.earthdatascience.org/courses/intro-to-earth-data-science/file-formats/use-text-files/format-text-with-markdown-jupyter-notebook/" target="_blank">**lesson**</a> in our **Earth Data Science** textbook that may be helpful.
>
> When adding <a href="https://www.w3schools.com/html/html_links.asp" target="_blank">**links**</a> and <a href="https://www.w3schools.com/html/html_images.asp" target="_blank">**images**</a> to your webpage, you may appreciate the added control of Hypertext Markup Language (HTML) over Markdown. 
>
> Get creative here!

## Step 3: Save your changes back to GitHub

The version control system `git`  wants to be *very* careful that you are sure you want to make changes before modifying anything. That means that there are actually 3 (three!) steps to saving your changes. You can do these in the JupyterHub git widget, or with git on the command line:

  ### 0a. Pull: ALWAYS make sure you have the latest from your remote repository on GitHub first!
  ### 0b. Take a look at which files git has determined have changes. Does it look right?
  
  1. Add: Mark which files you want to save changes for
  2. Commit: Bookmark the state of your local repository. **Make sure to add a commit message so you know what you did!**
  3. Push: Send your committed changes to the remote repository on GitHub

## Step 4: Check your website again
You know the drill!

**IMPORTANT:** Always remember to **commit changes** so that your updated content gets added to your webpage.

## All done? 
  * Share your website on KI Storm, Slack, or in the zoom chat!
  * <a href="https://pages.github.com/themes/" target="_blank"> Add a theme to your webpage.
