
# Learning to Contribute to GitHub: Cheatsheets
Don't forget to look at the git documents.
## We :heart: Contributors Like You!

# Set some goals to contrubute
#### Get familar with github

## Get the hang of the workflow:

[https://github.com/hackerkid/Mind-Expanding-Books]
[https://github.com/alebcay/awesome-shell]
[https://github.com/sindresorhus/awesome]

## Resources
[https://github.com/firstcontributions/first-contributions]
[https://github.com/freeCodeCamp/how-to-contribute-to-open-source]
[https://github.com/freeCodeCamp/how-to-contribute-to-open-source]
[https://github.com/MunGell/awesome-for-beginners]

## GitHub Resoruces

GitHub http://github.com 



[lab.github.com/courses] (https://lab.github.com/courses)

Mastering Gitlab markdown 
https://guides.github.com/features/mastering-markdown/



> Content based on
> <a href="https://github.github.com/training-kit/">github.github.com/training-kit/</a>
> used under the
> <a href="https://creativecommons.org/licenses/by/4.0/">CC-BY-4.0</a>
> license.</a>

Code used to build and test the site as well as code samples on the site, if any, are licensed under [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/legalcode). CC0 waives all copyright restrictions but does not grant you any trademark permissions.

This means you can use the content and code in this repository except for GitHub trademarks in your own projects.

When you contribute to this repository you are doing so under the above licenses.


## Forking Repos

- Fork repo to your local account and clone
- Check remote status 
```
git remote -v
```
- Specify the a remote upstream repo to sync with your fork
```
git remote add upstream https://github.com/OriginalOwner/OriginalProject.git
```
- Verify
```
git remote -v
``` 
- Checkout your forks local master then merge changes from upstream/master into it.
```
git checkout master
git branch
git merge upstream/master
```
- Push changes to update your fork 
```
git branch
git push
```