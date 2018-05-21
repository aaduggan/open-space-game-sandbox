# **Open-Space-Game**<br/>
_Open World, Open Space, Open Source :tm:_

This is the design document for the multi-genre, open-world, space adventure game, open-space-game.  Our intention, with this document, is to layout the overall vision of the project and how we might go about getting there.


# Table of Contents
* [Game Overview](#game-overview)
    * [Philosophy](#philosophy)
    * [Common Questions](#common-questions)
    * [Proposed Features](#proposed-features)
* [Campaigns](#campaigns)
    * [Nothing at all like Asteroids](#campaign-001)


# Game Overview

This section should give the reader the over-all concepts by which the project has been devised.

## Philosophy

The motivations and thought process that drives the spirit of the project.

### More Than You Can Chew

All too often projects get overwhelmed with the number of features and goodies that they want to deliver.   Many also try to deliver these features all at once which often makes for a confused and disorderly project.  In order to release sound software, it's often best to have discreet goals that, once fulfilled, allows for usable versions that others can experience.

We intend to lay the game out into separate Campaigns that will implement key features and technologies that will be carried forward into future Campaigns.  These Campaigns will be, themselves, broken down into Milestones that will be implemented through Projects.  While this document lays out the overall vision of the project, there will be separate (though similar) design documents for each Campaign.

### Quest to Make Money

One of the more disturbing trends with the game industry is the prevalence of entities who appear to be solely profit minded.  These entities will seemingly do anything to make a profit: turn their players into unpaid employees, require full payment for half finished games, rely on a mod community to bolster their game but then spend little to no resources on making it stable and convenient.  Once it was discovered that the game market would buy products sight-unseen; it has been a virtual bonanza with the players being the ones to pay the highest dividends.

We firmly believe that there must be some projects that are not profit minded.  Where the voices of the community are heard but not filtered through the colored lens of the profits required for a large corporation.  That some things should be done simply for the love of doing them and if you make money in the process; even better.  When profit, however, becomes the highest authority only but a few will get the reward.

## Common Questions

Below are some questions we feel a reasonable person might have in regards to this project.  If you have questions not presented here, please feel free to contact someone or open a question issue.

### What is the game?

Open-Space-Game is a mixed genre, open-world, multi-player game set in the near future that allows groups of players to cooperate/compete over the colonization and control of lands and assets within a star cluster.

### Why create this game?

There's no traditional reason to create this game, other than to satisfy some needs each of the developers have on a personal level.  This game is being created to provide a fun, technically challenging, task to do while potentially providing a foundation that other games like it can build upon for even better, commercially independent, games.

### Where does the game take place?

Due to the modifiable nature of open-space-game, this could be anywhere or anytime but the initial mod will take place in a planetary system surprisingly similar to ours with near future technology.

### What do I control?

The player can control just a single nomadic character, who owns little more than the clothing on their back, all the way up to full fledged organizations with both human and NPC members along with all the assets therein.

### How many characters do I control?

The number of characters controlled is up to the player.  As more tasks need to be done the player can recruit player or non-player characters to fulfill those roles.  As such there is no upper bound set outside of resource limitations.

### What is the main focus?

The player's focus is their own though the game should provide numerous activities that the player can engage in either individually or collectively to satisfy needs of their fellow players or whatever personal goals they wish to achieve.

### What’s different?

The focus and spirit of the project is what we think sets it apart: giving players a unique combination of activities, focusing on modification support and stability, and having no outside influence other than the community itself.


# Proposed Features

The game will be broken down into a number of extend-able events that will allow for game content and activities to be dynamically loaded.  Even with this level of dynamics there will be a central set of features that will include:

* Map mode for viewing the universe and planetary surfaces
    * Planetary Interaction
        * Celestial Information
        * Ground/Orbital Deployment
            * Industry
                * Mineral Extraction
                * Resource Processing
            * Transport Logistics
            * Commerce & Entertainment
            * Scanning Devices
        * Craft Deployment
    * Craft Course Plotting
        * Observe other objects and their potential course
* Game mode for interacting with the universe at large
    * Character interaction with single or multiple control-able characters
        * Locomotion
        * Object Use
        * AI Tasks
    * Manual craft interaction
        * Piloting
        * Actions
* Craft/Station/Facility modes
    * Similar to Game mode but for specific conditions
    * Linked to Game mode so internal actions can have exterior effect


# Campaigns

As previously mentioned, this project is going to broken down into Campaigns that will implement key features and technologies that will be expanded upon in future campaigns.

## Campaign #1 : [Nothing at All Like Asteroids](Design.Campaign.001.md)<a id="campaign-001"></a>

The initial iteration of open-space-game that should set up the most foundational elements of the project including:

    * Physics Implementation
    * Initial User Interface
    * Initial Scene Manager
    * Multi-player infrastructure
