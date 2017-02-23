This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

You can find the most recent guide for Create React App [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

## Video Shark

**Application Uses...**

```
  Youtube API
  Asyncronous Search
  Component-level State
```

**What does Video Shark do?**

Provides the five most popular videos based off of the search term that a user gives. It then serves the video and description of whichever link the user  chooses.

**How does it do this?**

The query from the user is almost immediately injected into a youtube API request and updates the state of the top-level component with the videos. When the state changes, the screen is updated with each video populating a list on the right side. The main video is then updated with the first video in that list.

**How can I try this out myself?**

There is a link at the top of the github page in order to view [Video Shark](https://jandersontech.github.io/video-shark/). 

Otherwise you can build the program yourself by following these steps:

1. Download the zip file from the Github repo or fork and clone the repo to your local directory either through Github or through git:

`git clone https://github.com/<your-profile-name>/video-shark`

2. Install node and npm onto you computer and run the following commands:

`npm install`
`npm start`