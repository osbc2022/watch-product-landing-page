<h1 align=center> How To Contribute ? </h1>

<details align=center>
<summary>Table of content</summary>

<p align=center>

| Topics               | links to each section |
|----------------------|-----------------------|
|Create a issue        |[link]()       |
|Fork the repo         |[link]()       |
|Clone the repo        |[link]()       |
|Add remote links      |[link]()       |
|Create a branch       |[link]()       |
|Make changes          |[link]()       |
|Stage, commit & push  |[link]()       |
|Make a PR :smile:     |[link]()       |

</p>

</details>

## Create a issue / ask to get assigned to existing issues :-
- the repository in which you want to contribute, in this case `osbc2022/watch-product-landing-page`, we will call this the __*"original repo"*__
- In the original repo look at the top bar of the code folders and go to `issues`

  - check if your issue is already present by searching or simply scrolling down through all the issue :sweat_smile:, now there could be 2 senarios:-
    1. __if your issue is not previosly present :-__
      - go on create a new issue, and comment below mentioning the admin to assign the issue to you
      - wait until you get the issue assigned to you , make sure have enabled notifications ([click to know more]()).
    2. __if your issue is already present :-__
      - check if it is assigned to any one, you can do this by checking the comments, if you se something like `obsc2022 assigned "any-user-name"`, then it's alredy assigned to someone find some other issue. If it's not assigned to any one then comment and ask to be assigned (you can also check the lables)
- you can check, how to write proper [issues]() down below.


## 1) Fork the project :

- Check on the upper right corner of the original repo and `fork` the project by clicking on it.
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


### Check out these resources before you get started:-

or you can just check them on the go, when required

|Description of the resources| links |
|----------------------------|-------|
|write proper issues         | [link]()|
|write proper commit messages| [link]()|
|code od conduct             |[link]()|