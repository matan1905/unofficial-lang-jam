# Unofficial lang Jam
So this is a programming language jam but it's not by the original creators of the [Original jam](https://github.com/langjam/langjam) so I call it unofficial.
There are no prizes, however there will be voting for the winner.

The jam theme is: **not yet announced.**

Bonus street cred if you could also include the theme: **NOT YET ANNOUNCED**

## Getting started
anyone can participate, if you or your team would like to add a submission:
* Create your own git repo with the project name, keep it family friendly.
* Create the best programming language in that repo
* Send a PR containing that repo as a [submodule](https://github.blog/2016-02-01-working-with-submodules/) (scroll down for a quick example)

submodules names are first come first serve.

Thanks to submodules magic, you could then keep working on your repo and when time is due I will update all repos to the latest submission.

## Your Project
Your project repo should contain the language source
To make everyone's life easier please include the following in your readme:
* Full instructions on how to start writing in your language
	* Build instructions - all tools must be included in a default linux installation or at most 3 steps
	* documentation
* Sample files written in your language (and what they do if it's a cryptic language)
* Explanation of how it relates to the theme

## Timeline
Starting: 14 May at 7:00 am UTC

Ending at: 21 May at 7:00 am UTC

You can work on the language for as long as you want within that timeframe.

## Judging
The judging will be done by the community using some voting site
winner will be announced 2 weeks after the jam ends.
These are the judging parameters:
* Language documentation
* Language Creativity
* Language Uniqueness

The bonus street cred in the bonus theme may also be a considering point.

## Help
if you need any kind of help you can use the [discourd group](https://discord.gg/YxuJPVuyQ9)

### How to add your project as a submodule
```bash
# step 1: have a github repo of your project
# step 2: clone this repo
git clone https://github.com/matan1905/unofficial-lang-jam.git && cd unofficial-lang-jam
# step 2.54: create and move to a new branch
git checkout <branch name>
# step 3: link your project as a submodule
git submodule add <your project github url> <project name>
# step 4: save your changes and push it
git add .
git commit -m "Adding submission"
git push
```
After doing all of these you can come back to this repository and add your pull request
