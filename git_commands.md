<h1> Git and Github </h1>

<h2> Task 1</h2>
<p>Demonstration of basic Git command with explanation and screenshot</p>
<hr>
<p>1. Git clone - this command helps copying the whole repository (master branch) to your local system.</p>

`git clone "url://github_repo_url"`

![Git clone command](https://github.com/vrundag91/git_commands/blob/master/git-commands-screenshot/git-clone.PNG)

<hr>

<p>2. git config --global user.name - This command will set your given name as your user name. This is used for authorization process on GitHub.</p>

<p>set username</p>

`git config --global user.name "your_name"`

<p>check username</p>

`git config --global user.name`

![Git clone command](https://github.com/vrundag91/git_commands/blob/master/git-commands-screenshot/git-username.PNG)

<hr>

<p>3. git config --global user.email - This command will set your given email address as your user email. This is also used for authorization process on GitHub.</p>

<p>set email</p>

`git config --global user.email "your_email_address"`
<p>check email</p>

`git config --global user.email`

![Git clone command](https://github.com/vrundag91/git_commands/blob/master/git-commands-screenshot/git-useremail.PNG)

<hr>

<p>3. git status - This command shows the status of the file -- untracked -- unmodified -- modified -- staged</p>

`git status`

![Git clone command](https://github.com/vrundag91/git_commands/blob/master/git-commands-screenshot/git-status.PNG)

<hr>

<p>4. git status -s - This command show the status in shot representation - the first position shows staged status and second position shows working tree status</p>

`git status -s`

![Git clone command](https://github.com/vrundag91/git_commands/blob/master/git-commands-screenshot/git-status-short.PNG)

<hr>

<p>4. git add filename - This command will send the file in staged status</p>

`git add "your_file_name"`

![Git clone command](https://github.com/vrundag91/git_commands/blob/master/git-commands-screenshot/git-add-file.PNG)

<hr>

<p>5. git add . <b>OR</b> git add -A - This command will add all files togather</p>

`git add .`

`git add -A`

![Git clone command](https://github.com/vrundag91/git_commands/blob/master/git-commands-screenshot/git-add-all.PNG)
