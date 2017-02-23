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