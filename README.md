<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Project week 3 (Gnoosic)
*Filipe Santos*

*Data Analytics*

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Links](#links)

## Project Description
This project consists in building a system that suggests some songs based on an input of a song from a user.

## Rules
After opening the notebook the user only needs to type the name o a song. If the song is in the Top 100 of Billboard, another song from that top will be suggested, otherwise, a song with similar features will be suggested.

## Workflow
1. Get the top100 Billboard Charts and create a big dataset with more than 10.000 songs;
2. Through Spotify API, get the features of the songs of our dataset;
3. Create some clusters (8 Clusters were created) to group the songs by the features;
4. Find the features of song chosen by the user through Spotify API, and then return a suggestion of a song that fits in the same cluster of features. 


## Links

[https://github.com/FilipeMiguelSantos/FilipeMiguelSantos/Project_week3

