# test-tutorial
This repo will just be to test push/pull and make sure everything works 

## Setting Up
1. Fork the repo (are we doing this?. Repo stands for "repository". 

## Option 1: Using GitHub Desktop
1. Download <a href = https://desktop.github.com/ >Github for Desktop</a>

## Option 2: Using the Terminal
<i> For this tutorial, any code in {curly brackets} is pseudo-code, meaning do not actually type the exact words in the brackets into the terminal. Instead, type whatever is indicated by the brackets. If your project name is "apples", then type "apples" instead of {proj-name}, e.g. <code>cd apples</code> </i>
1. After forking the repo, copy the link to clone the repo. This can be done with <code>ssh</code> keys if that's been set up (it seems like this is technically safer, so I might go over that, this can be a seperate section). Otherwise, we'll be using the <code>https</code> version. <br><br>  i. Under <i> Code >> Clone >> HTTPS</i>,  copy the URL, which will have the format: https://github.com/{username}/{proj-name}.git
2. Open the terminal <br> <br> i. Go to the correct working directory. To do this, type <code>cd ~Desktop/{tutorial}</code>, where tutorial can be any folder or directory you want it to be (the files could exist in the F Drive or Box). <br><br>ii. To check that you're in the corrcet working directory, you can type <code>pwd</code> in the command line to <i>print working directory</i> 
3. Cloning and cd-ing into the Repository (or the Repo) <br><br> i. Now that you're in the correct working directroy, you can now clone the repository. To do this, in the command line terminal, type <code>git clone {git url from earlier}</code>. <br><br>ii. The shell will ask you to login to your github account. Normally, you can just enter your usernmae and password to get into the repo. However, if an error pops up about failef authentication and safet, then you may need to make a <a href= "https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token">personal access token</a>. <br><br>iii. Now that you have the proper files, it is time to <i>cd</i> into the project, or essentially get into the correct file structure in order to access all the files you just cloned from Github. To do this, first you can list all the files in your current working directory by typing <code>ls</code>. The only file that should be listed at the moment will be the <i>{proj-name}</i>. <br><br>iv. To then cd into that project's directory, type <code> cd {proj-name}</code>
4. The next steps have to do with adding remotes, but that's only based off forking so we'll leave that for now
5. 
