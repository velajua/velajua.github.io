---
layout: post
title: Instagram Sudoku Deployer
subtitle: A Graph API connection to manage the deployment of Sudokus to the [`Sudoku Puzzle Daily`](https://www.instagram.com/sudoku_puzzle_daily/) instagram page. 
gh-repo: velajua/instagram-sudoku-deployer
gh-badge: [star, fork, follow]
thumbnail-img: /assets/img/sudoku-logo.jpeg
cover-img: /assets/img/python-banner_.jpg
tags: [Python, API, Instagram, Docker, Flask]
comments: true
---

This [`repository`](https://github.com/velajua/instagram-sudoku-deployer) creates the deployment of Sudoku images and their solutions to an instagram page: [`Sudoku Puzzle Daily`](https://www.instagram.com/sudoku_puzzle_daily/). It also manages the replies for the latest comments.

## Requirements

Python 3.x

GCloud. The code makes use of the `Google Cloud Secret Manager` for all of the Graph API token keys as well as the freeimage hosting service API keys.

The requirements can be installed by using `pip install -r requirements.txt`

## Instagram page
The [`Sudoku Puzzle Daily`](https://www.instagram.com/sudoku_puzzle_daily/) instagram page is as follows:
![sudoku instagram page](/assets/img/sudoku-page.png)

It contains sudokus ranging from 2*3/3*2 to 4*5/5*4. They contain normalized difficulties. 

## Usage
- The repository contains a Dockerfile for deployment (The Cloud Run URL used contains Google Authentication for server protection).
- Although a Dockerfile is provided, as the code references a `Google Cloud Secret Manager` secret, the code won't run in local unless modified.
