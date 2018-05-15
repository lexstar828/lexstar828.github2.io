# Project Overview
Strava Clubs Activity Heatmap & Statistics

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.

|  Day | Deliverable | Status
|---|---| ---|
|May 1st| Project Description | Complete
|May 8th| Wireframes / Priority Matrix / Functional Components | Incomplete
|May 15th| External API(s) Decision / Core Application Structure (HTML, CSS, etc.) | Incomplete
|May 22nd| Minimal Viable Product | Incomplete
|May 29th| Styling / Bug Fixes | Incomplete


## Project Description

The goal for my final project will be to visualize/break down the data retrieved from Strava (running app) for a running group called “Canaw”.


The goal is to extract the information from Stravas club API and use it to determine location per runner, as well as distance per runner.

Then that information would be sorted based on proximity, maybe by countries, regions or cities (still undecided).

Ideally the final result should be dynamic, and should show current data. The grouping will be displayed in either table or a heat map (that would involve a map API, ie; google maps).

The idea is to visualize the running activity as a whole group, to unite the members more & the encourage the less athletic participants (rather than show the leaders and their best times and distance).

Canaw - Can and will

## Wireframes
[Wireframe external link](https://wireframe.cc/txJUm1)

![wireframe](https://res.cloudinary.com/lexstar828/image/upload/v1525991882/wireframe1.1.jpg)


## Priority Matrix


 ![Priority Matrix](https://res.cloudinary.com/lexstar828/image/upload/v1526414525/matrixp.jpg)
  

### MVP/PostMVP - 5min

The functionality will then be divided into two separate lists: MPV and PostMVP.  Carefully decided what is placed into your MVP as the client will expect this functionality to be implemented upon project completion.  

#### MVP 

- Use Strava Club API to pull club information
- Render heatmap of activity with Google Maps API
- Render data for all users (total distance) 


#### PostMVP 

- Add export data function

## Functional Components

Based on the initial logic defined in the previous  phases section try and breakdown the logic further into functional components, and by that we mean functions.  Does your logic indicate that code could be encapsulated for the purpose of reusablility.  Once a function has been defined it can then be incorporated into a class as a method. 

Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. 

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Strava Club API | H | 3hrs| | |
| Static header (Club/member selector) | H | 3hrs|  |  |
| Integration into Google Maps Api (heat map) | H | 4-5hrs| | |
| HTML CSS | H | 1hr| | |
| Total | H | 12hrs|  |  |

![Functional Components](https://res.cloudinary.com/lexstar828/image/upload/v1525992189/pm.png)

## Helper Functions
Helper functions should be generic enought that they can be reused in other applications. Use this section to document all helper functions that fall into this category.

| Function | Description | 
| --- | :---: |  
| blank | blank | 

## Additional Libraries
 
 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description  

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```

## jQuery Discoveries
 Use this section to list some, but not all, of the jQuery methods and\or functionality discovered while working on this project.

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  

## Issues and Resolutions
 Use this section to list of all major issues encountered and their resolution.

#### SAMPLE.....
**ERROR**: app.js:34 Uncaught SyntaxError: Unexpected identifier                                
**RESOLUTION**: Missing comma after first object in sources {} object
