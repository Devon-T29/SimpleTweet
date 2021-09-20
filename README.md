# Project 2 - *Simple Tweet*

**Simple Tweet** is an android app that allows a user to view his Twitter timeline. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **7** hours spent in total

## User Stories

The following **required** functionality is completed:

- [ x] User can **sign in to Twitter** using OAuth login
- [x ]	User can **view tweets from their home timeline**
  - [x ] User is displayed the username, name, and body for each tweet
  - [x ] User is displayed the [relative timestamp](https://gist.github.com/nesquena/f786232f5ef72f6e10a7) for each tweet "8m", "7h"
- [ x] User can refresh tweets timeline by pulling down to refresh

The following **optional** features are implemented:

- [x ] User can view more tweets as they scroll with infinite pagination
- [ ] Improve the user interface and theme the app to feel "twitter branded"
- [ ] Links in tweets are clickable and will launch the web browser
- [ ] User can tap a tweet to display a "detailed" view of that tweet
- [ ] User can see embedded image media within the tweet detail view
- [ ] User can watch embedded video within the tweet
- [ ] User can open the twitter app offline and see last loaded tweets
- [ ] On the Twitter timeline, leverage the CoordinatorLayout to apply scrolling behavior that hides / shows the toolbar.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/Devon-T29/SimpleTweet/blob/master/SimpleTwitter.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [ScreenToGif](https://www.screentogif.com/).

## Notes

Didn't face any challenges but I did find out during my submission that the timestamp requirement was skipped over in the video walkthroughs, but I have gained enough knowledge to use the instructions provided and implement them myself. I will continue with some of the strech stories later I just do not have the time to continue with them before the project due date.

# Project 2 - *SimpleTweet Part2*

**SimpleTweet** is an android app that allows a user to view his Twitter timeline and post a new tweet. The app utilizes [Twitter REST API](https://dev.twitter.com/rest/public).

Time spent: **6** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x ] User can **compose and post a new tweet**
  - [ x] User can click a “Compose” icon in the Action Bar on the top right
  - [x ] User can then enter a new tweet and post this to twitter
  - [ x] User is taken back to home timeline with **new tweet visible** in timeline
  - [x ] Newly created tweet should be manually inserted into the timeline and not rely on a full refresh
  - [ x] User can **see a counter with total number of characters left for tweet** on compose tweet page

The following **optional** features are implemented:

- [ ] User is using **"Twitter branded" colors and styles**
- [ ] User can click links in tweets launch the web browser 
- [ ] User can **select "reply" from detail view to respond to a tweet**
- [ ] The "Compose" action is moved to a FloatingActionButton instead of on the AppBar
- [ ] Compose tweet functionality is build using modal overlay
- [ ] Use Parcelable instead of Serializable using the popular [Parceler library](http://guides.codepath.org/android/Using-Parceler).
- [x ] User can **open the twitter app offline and see last loaded tweets**. Persisted in SQLite tweets are refreshed on every application launch. While "live data" is displayed when app can get it from Twitter API, it is also saved for use in offline mode.
- [ ] When a user leaves the compose view without publishing and there is existing text, prompt to save or delete the draft. If saved, the draft should then be **persisted to disk** and can later be resumed from the compose view.
- [ ] Enable your app to receive implicit intents from other apps. When a link is shared from a web browser, it should pre-fill the text and title of the web page when composing a tweet. 

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/Devon-T29/SimpleTweet/blob/master/SimpleTwitterPart2.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [ScreentoGif](http://www.screentogif.com/).

## Notes

Learning how to implement the character counter.
## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Devon Traywick]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
