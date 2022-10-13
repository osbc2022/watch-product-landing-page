<h1 align=center> How To Contribute ? </h1>

<details align=center>
<summary>Table of content</summary>

<p align=center>

| Topics               | links to each section |
|----------------------|-----------------------|
|Create a issue        |[link](https://github.com/osbc2022/watch-product-landing-page/edit/main/.github/CONTRIBUTING.md#-create-a-issue--ask-to-get-assigned-to-existing-issues--)       |
|Fork the repo         |[link](https://github.com/osbc2022/watch-product-landing-page/blob/main/.github/CONTRIBUTING.md#1-fork-the-project-)       |
|Clone the repo        |[link](https://github.com/osbc2022/watch-product-landing-page/blob/main/.github/CONTRIBUTING.md#2-clone-the-fork-)       |
|Add remote links      |[link](https://github.com/osbc2022/watch-product-landing-page/blob/main/.github/CONTRIBUTING.md#3-add-remote-links-)       |
|Create a branch       |[link](https://github.com/osbc2022/watch-product-landing-page/blob/main/.github/CONTRIBUTING.md#4-create-a-branch)       |
|Make changes          |[link](https://github.com/osbc2022/watch-product-landing-page/blob/main/.github/CONTRIBUTING.md#5-make-required-changes-smile)       |
|Stage, commit & push  |[link](https://github.com/osbc2022/watch-product-landing-page/blob/main/.github/CONTRIBUTING.md#6-stage-commit--push-)       |
|Make a PR :smile:     |[link](https://github.com/osbc2022/watch-product-landing-page/blob/main/.github/CONTRIBUTING.md#7-make-a-pr-pull-request)       |

</p>

</details>

## 👣 Create a issue / ask to get assigned to existing issues :-
- the repository in which you want to contribute, in this case `osbc2022/watch-product-landing-page`, we will call this the __*"original repo"*__
- In the original repo look at the top bar of the code folders and go to `issues`
![image](https://user-images.githubusercontent.com/115569958/195557470-3a357601-bbc2-4122-86a2-15c681cb1725.png)
  - check if your issue is already present by searching or simply scrolling down through all the issue :sweat_smile:, now there could be 2 senarios:-
    1. __if your issue is not previosly present :-__
      - go on create a new issue, and comment below mentioning the admin to assign the issue to you
      ![image](https://user-images.githubusercontent.com/115569958/195557689-66b44559-36b1-4f9f-aa2c-f2c94e6e5f6b.png)
      - wait until you get the issue assigned to you , make sure have enabled notifications ([click to know more]()).
    2. __if your issue is already present :-__
      - check if it is assigned to any one, you can do this by checking the comments, if you se something like `obsc2022 assigned "any-user-name"`, then it's alredy assigned to someone find some other issue. If it's not assigned to any one then comment and ask to be assigned (you can also check the lables)
- you can check, how to write proper [issues]() down below.


## 1) Fork the project :

- Check on the upper right corner of the original repo and `fork` the project by clicking on it.
![image](https://user-images.githubusercontent.com/115569958/195557924-70f4d366-9587-49c2-8311-d7adb36fb824.png)
- This will create a copy of the project in your repositories section. example `your-github-user-name/watch-product-landing-page` we will call this a __*"forked repo"*__

<br/>

## 2) Clone The Fork :

 - Now clone the forked repo into your local machine. you can do this by pasteing the below command

 > _NOTE :- :exclamation: don't include this :point_right: " $ " , while coping the command_

```Shell
$ git clone https://github.com/osbc2022/watch-product-landing-page
``` 
Now you have the project on your local machine.

- now go to that directory 
```Shell 
$ cd ./watch-product-landing-page
```

> _Tip :- :heavy_check_mark: write `cd watch-` and press `Tab` key for autocompletion in the terminal._

<br/>

## 3) Add remote links :

_We will be adding 2 remote links
 - __origin__  :- the url of the forked repo 

  > _NOTE :- :exclamation: don't include this :point_right: " $ " , while coping the code,
  replace "paste-your-forked-repo-url-here" with your forked repo url(you can find this in your repositories section)_

```Shell
$ git add remote origin "paste-your-forked-repo-url-here"
```
- __upstream__ :- the url of the original repo

```Shell
$ git add remote upstream https://github.com/osbc2022/watch-product-landing-page
```

<br/>

## 4) Create a branch 

- create a branch with the issue number (recommended practice) , it's just a convention we follow, we will know why we do so down below.

 > _NOTE :- :exclamation: don't include this :point_right: " $ " , while coping the code,
 replace any-number with your issue number_

```Shell
$ git branch issue#(any-number)
$ git checkout issue#(any-number)
```
> _Tip :- :heavy_check_mark: write `git checkout issue` and press `Tab` key for autocompletion in the terminal._

<br/>

## 5) Make Required Changes :smile:

Now you are ready to make required changes to for contribution :thought_balloon:

<br/>

## 6) Stage, Commit & Push :  

- put all changes to [staging]()

 > _NOTE :- :exclamation: don't include this :point_right: " $ " , while coping the code_

```Shell
$ git add .
```
- commit the changes with a commit message

> _Note :  a commit message should be a short description of chages you made, example - `fix: inproper link redirections`, `feat: search bar created` you can check how to write proper [__commit message__]() below_ 

```Shell
$ git commit -m "done-something"
```

- push changes to the forked repo url (upstream)

```Shell
$ git push -u origin "branch-name"
```
> _Tip :- :heavy_check_mark: write `git push -u origin issue` and press `Tab` key for autocompletion in the terminal. that is why we recommend to use issue#(issue no.) as branch name it comes in handy, because you may not remember the branch name and also it helps us to close issue if you forgot to mention issue no. in your PR :point_down:, however you can check your current branch by `git stauts`._

<br/>

## 7) Make a PR (Pull Request)

Now you will be able to see the pull request button or contribue button on your forked repo in the github, now just go on and make a pull request and do not forget to mention the issue number you solved :point_right: `closes #1` , :heart: happy contributing :smile:


### 📌 Check out these resources before you get started:-

or you can just check them on the go, when required

|Description of the resources| links |
|----------------------------|-------|
|write proper commit messages| [link]()|
|code od conduct             |[link]()|
|licence                     |[link]()|