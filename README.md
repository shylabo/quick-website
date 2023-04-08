# Overview

This is a powerful application that enables you to quickly build a website using HUGO, a popular open-source static site generator. With its intuitive interface and customizable features, the application streamlines the website-building process, making it easy for users to create professional-looking sites in a matter of minutes.

# Gettings up and running

1. Run `npm install` to get all your node packages installed
2. Run `hugo` to build
3. Run `hugo serve` to get the server up
4. Visit http://localhost:1313/ to see site

# What is HUGO?

Hugo is one of the most popular open-source static site generators. With its amazing speed and flexibility, Hugo makes building websites fun again.
<br/>
https://gohugo.io/

## how to build a website with hugo

```
hugo new site {webSiteName}
```

```
cd {webSiteName}
hugo new theme {themeName}
```

In this case, I chose windytheme

```
npm init -y
npm install --save-dev autoprefixer postcss postcss-cli postcss-import tailwindcss
```

```
mkdir -p themes/windytheme/assets/css/
touch themes/windytheme/assets/css/postcss.config.js
touch themes/windytheme/assets/css/tailwind.config.js
touch themes/windytheme/assets/css/styles.scss\n
```

```
hugo server
```
