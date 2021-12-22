# Angela's Personal Portfolio

## Description
This portfolio is forked from [tbakerx's react resume template](https://github.com/tbakerx/react-resume-template). Besides personalizing the content, I used [particles-bg](https://github.com/lindelof/particles-bg), a react background particle library to make the home page more dynamic.


### What I Hope to Implement In the Future
- hosting on my own domain (not just github pages)
- a filtering system for my projects based on category
- popup / expanding effect when hovering over my projects


### Issues I Faced
The biggest issue I faced was hosting the website on github from the correct subfolder `public`. My solution was to create another branch called `gh-pages` which holds all the content `public`. I then deployed using `gh-pages`'s root folder.

The downside is, every time I change something in `master` that is in the `public` folder, it means I also need to run the following afterwards, to update `gh-pages` as well:

```shell
git subtree push --prefix public origin gh-pages
```

## Installing and Running the Project
The live link to the website can be accessed [here](https://azhang4216.github.io/portfolio/).

### 1. Clone the project
```shell
git clone https://github.com/azhang4216/portfolio.git
```

### 2. Run the project
```shell
npm i
npm start
```

### 3. Build
```shell
npm run build
```