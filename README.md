# IndexedDB
taking an existing application and hooking IndexedDB in to allow offline functionality

## Features
* the ability to handle (add) transactions while offline
* when back online, will push offline transactions into the db

## Reasoning
Offline capabilities are a hallmark of PWAs, which is what we have implemented here. There is no guarantee that the client will have their internet access be reliable across time, but you can make it so that doesn't matter.

## Challenges & Process
1. I basically grabbed snippets from previous activities to set up the manifest, service-worker and IndexedDB functionality; which to be honest worked fairly quickly and easily.

2. Deploying to Atlas for Heroku was again a fairly straight forward process, I used the walkthrough from the previous weeks activities/homework.

## Link to repo
[Repo](https://github.com/bendemic90/IndexedDB)

## Link to deployed website
[Heroku]()