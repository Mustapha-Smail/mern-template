# mern-template

A MERN stack application template 

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/dae3c9f1d6fd4210b658db0e6a21cdc9)](https://app.codacy.com/gh/Mustapha-Smail/mern-template?utm_source=github.com&utm_medium=referral&utm_content=Mustapha-Smail/mern-template&utm_campaign=Badge_Grade_Settings)
[![Build Status](https://app.travis-ci.com/Mustapha-Smail/mern-template.svg?branch=main)](https://app.travis-ci.com/Mustapha-Smail/mern-template)
[![License](https://img.shields.io/github/license/mustapha-smail/mern-template.svg?style=flat-square)](LICENSE)
[![Tag](https://img.shields.io/github/tag/mustapha-smail/mern-template.svg?label=tag&style=flat-square)](https://github.com/Mustapha-Smail/mern-template/releases/latest)
[![Release](https://img.shields.io/github/release/mustapha-smail/mern-template.svg?style=flat-square)](https://github.com/Mustapha-Smail/mern-template/releases/latest)

## Requirments 
*In order to build and run the application you need:* 
- [Node js (LTS)](https://nodejs.org/en/download/)

## Before Running the app locally 

- First you need to clone the code source into your local machine : 
```shell
git clone git@github.com:Mustapha-Smail/mern-template.git
```
*NB: you need to setup an SSH key on your github account first*

- Go to your app folder, and run this command: 
```shell
npm install 
```

- Create a file name `.env` in your root folder and set the port you want your backend to run in : <br>
*By default it's 5000* 
```shell
PORT=5000
```
- Create another `.env` file in the `frontend` folder and set the URL of your backend : <br>
*DO NOT change the variable name* 
```shell
REACT_APP_BE_URL=http://localhost:5000/
```
## Run the app locally 

This section explains to you how to run this application locally <br>

- Open the terminal, go to the root folder of your app : 
    - To run the app : 
        ```shell
        npm run start
        ```
    - To run the app in dev environment : 
        ```shell
        npm run dev
        ```
    - To run the test : 
        ```shell
        npm run test
        ```
    - To run only backend : 
        ```shell
        npm run server
        ```
    - To run only frontend : 
        ```shell
        npm run client
        ```


