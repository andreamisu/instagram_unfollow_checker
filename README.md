# Instagram Unfollow Checker

A crystal clear Python Instagram unfollowers tracking, and *nothing* more.

![Python 2.7, 3.5](https://img.shields.io/badge/Python-2.7%2C%203.5-3776ab.svg?maxAge=2592000)

## Overview

Using 3rd parties application for tracking unfollowing users on Instagram might be a hustle, they can use your profile for following unwanted people, liking posts, and else.
This will do nothing of all those things, just export in a **really nice** .txt whose unfollowing you >:-(((

## Features

- 1.0 release includes:
    * Dump unfollowing users into a .txt log file
    * Token saving and relay for avoiding multiple access to your profile (very important!!)

- Future implementation:
    * support on auto-unfollowing those bad people 
    * Not-Following-Me-Back feature, including auto-unfollowing
    * ?????? feel free to suggest in "Issue"! x

## Install

- Dependencies:
    * Pip 
    * Python (tested on Python 3.9)

Execute dependencies installer:

``./dependencies.sh``

Execute ``Install Certificates.command`` inside your Python Application Folder (where you've installed Python) to allow SSL Local Certificate Issuer.

## Usage

Execute ``python3 unfollower_checker.py -u "xxxx" -p "yyyy" -settings "zzzz.json"``

change "xxxx" with your **Instagram name**, "yyyy" with your **password**, "zzzz.json" with the name of the file in which you want to save the **login token** (it's automatically created by the program!)

## GG WP! 

Mostly based on Ping's [Instagram private API](https://github.com/ping/instagram_private_api), 
[so go buy him a coffee!](https://www.buymeacoffee.com/ping)

Thanks to @bwitch_ and @grlvoid for **spiritual** and **corporate** guidance.