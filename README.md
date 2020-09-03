# Project 3 - *Instagram App Part 1*

**Instagram App** is a photo sharing app similar to Instagram but using Parse as its backend.

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can sign up to create a new account using Parse authentication.
- [x] User can log in and log out of his or her account.
- [x] The current signed in user is persisted across app restarts.
- [x] User can take a photo, add a caption, and post it to "Instagram".

The following **optional** features are implemented:

- [ ] User sees app icon in home screen and styled bottom navigation view
- [ ] Style the feed to look like the real Instagram feed.
- [ ] After the user submits a new post, show an indeterminate progress bar while the post is being uploaded to Parse.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/DevPopat/InstaAppPart2/blob/master/walkthrough-1.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Recordit](https://recordit.co).

## Notes

This project was my first exposure to creating my very own cloud database using Heroku (or any other cloud service for that matter). It was really exciting to see how data is stored in the backend using set requests and retrieved using get requests. Understanding the ParseDashboard was a little difficult at first because I had never been exposed to an environment like it, however, I got used to it pretty quickly and realised it was very easy to create models/classes on the ParseDashboard. I also found that it helped me visualize my app at a macro level.
Interacting with the phone camera was a convoluted task. It required a lot of interaction with storage directories of the phone, retrieving files and launching the camera app of the phone. The hard part of this feature was not accessing the camera but retrieving the image from the storage directories. Reading the documentation and CodePath guides a couple of times helped a lot in getting this done.
## Open-source libraries and technologies used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
- [Heroku](https://www.heroku.com/) - ParseDashboard for cloud backend database


## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.


# Project 3 - *Instagram App Part 2*

**Instagram App** is a photo sharing app similar to Instagram but using Parse as its backend.

Time spent: **5** hours spent in total

## User Stories

The following **required** functionality is completed:

- [x] User can view the last 20 posts submitted to "Instagram".
- [x] User can pull to refresh the last 20 posts submitted to "Instagram".
- [x] The user should switch between different tabs - viewing all posts (feed view), capture (camera and photo gallery view) and profile tabs (posts made) using fragments and a Bottom Navigation View. (2 points)

The following **optional** features are implemented:

- [ ] Style the feed to look like the real Instagram feed.
- [ ] User can load more posts once he or she reaches the bottom of the feed using infinite scrolling.
- [ ] Show the username and creation time for each post.
- [ ] User can tap a post to view post details, including timestamp and caption.
- [ ] User Profiles
      - [ ] Allow the logged in user to add a profile photo
      - [ ] Display the profile photo with each post
- [ ] Tapping on a post's username or profile photo goes to that user's profile page and shows a grid view of the user's posts
- [ ] User can comment on a post and see all comments for each post in the post details screen.
- [ ] User can like a post and see number of likes for each post in the post details screen.
- [ ] Run your app on your phone and use a custom camera view

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/DevPopat/InstaAppPart2/blob/master/07klmOl2rT.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Recordit](https://recordit.co).

## Notes

One of the challenges I faced was converting all of my activities to fragments from part 1 of the app. This conversion was a convoluted process as it required me to create separate fragment activities, create the bottom navigation bar and icons for each of the options. Using fragments also changed the way to create adapters for recycler views. Like for example you need to use the function call "getContext()" rather than ".context" to get the current state of the application. It also changed the way we use "findViewById()" which also took a little getting used to. After this project, I have realized that fragments are an efficient alternative to creating separate activities. It sets apart the amateur developers from the experiences ones. I feel it was definitely worth the effort as it makes the more concise (fewer activities) and easier to use.
I feel as a future goal I can definitely work towards making a more appealing design as it is an important part of the user experience. Using some Instagram related assets would give the app a more professional look.
## Open-source libraries and technologies used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
- [Heroku](https://www.heroku.com/) - ParseDashboard for cloud backend database


## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
