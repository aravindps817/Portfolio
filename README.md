# Port Folio ⚡️ [![GitHub](https://img.shields.io/github/license/saadpasta/developer-portfolio?color=blue)]

## A clean, beautiful and responsive portfolio template for Developers!


## Sections 
✔️ Summary and About me\
✔️ Skills\
✔️ Work Experience\
✔️ Open Source Projects Connected with Github\
✔️ Contact me\
✔️ Twitter Timeline\
✔️ Github Profile


```
node@v10.16.0 or higher
npm@6.9.0 or higher
git@2.17.1 or higher
```


## How To Use 🔧

From your command line, clone and run developerFolio:

```bash
# Clone this repository
$ git clone https://github.com/saadpasta/developerFolio.git

# Go into the repository
$ cd developerFolio

# Install dependencies
$ npm install

#Start's development server
$ npm start
```
## Github Setup For Open Source Projects

Generate a Github personal access token using these [Instructions](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line) `Make sure you don't select any scope just generate a simple token`

1. Create a file called .env in the root directory of your project.

```bash
- DeveloperFolio
  - node_modules
  - public
  - src
  - .env         <-- create it here
  - .gitignore
  - package-lock.json
  - package.json
```

2. Inside the .env file, add key `REACT_APP_GITHUB_TOKEN` and assign your github token like this.

```javascript
 // .env

  REACT_APP_GITHUB_TOKEN = "YOUR GITHUB TOKEN HERE"

};
```

Set `showGithubProfile` to true or false to show Contact Profile using Github, defaults to false.

## Change and customize every section according to your need.

#### Personalize page content in `/src/portfolio.js` & modify it as per your need.



#### Using Emojis

For adding emoji 😃 into the texts in `Portfolio.js`, use the `emoji()` function and pass the text you need as an argument. This would help in keeping emojis compatible across different browsers and platforms.

#### Adding Twitter Time line to your Page
Insert your Twitter username in `portfolio.js` to show your recent activity on your page.

```javascript
const twitterDetails = {
  userName : "Your Twitter Username"
};
```
Note: Don't use `@` symbol when adding username.

## Deployment 📦 
When you are done with the setup, you should host your website online.
We highly recommend to read through the [Deploying on Github Pages](https://create-react-app.dev/docs/deployment/#github-pages) docs for React.

#### Deploying to Github Pages

This section guides you to deploy your portfolio on Github pages.

- Navigate to `package.json` and enter your domain name instead of `https://developerfolio.js.org/` in `homepage` variable. For example, if you want your site to be `https://<your-username>.github.io/developerFolio`, add the same to the homepage section of `package.json`. 

- In short you can also add `/devloperFolio` to `package.json` as both are exactly same. Upon doing so, you tell `create-react-app` to add the path assets accordingly. 

- Optionally, configure the domain. You can configure a custom domain with GitHub Pages by adding a `CNAME` file to the `public/` folder.

- Follow through the guide to setup GitHub pages from the official CRA docs [here](https://create-react-app.dev/docs/deployment/#github-pages).


## Technologies used 🛠️

- [React](https://reactjs.org/)
- [graphql](https://graphql.org/) 
- [apollo-boost](https://www.apollographql.com/docs/react/get-started/) 
- [react-twitter-embed](https://github.com/saurabhnemade/react-twitter-embed)
- [react-easy-emoji](https://github.com/appfigures/react-easy-emoji)
- [color-thief](https://github.com/lokesh/color-thief)


