# Project 3 - *Parstagram Part 2*

**Parstagram** is a photo sharing app similar to Instagram but using Parse as its backend.

Time spent: **7** hours spent in total

## User Stories

The following **required** functionality is completed:

- [X] User can view the last 20 posts submitted to "Instagram".
- [X] The user should switch between different tabs - viewing all posts (feed view), compose (capture photos form camera) and profile tabs (posts made) using fragments and a Bottom Navigation View. (2 points)
- [X] User can pull to refresh the last 20 posts submitted to "Instagram".

The following **optional** features are implemented:

- [X] User sees app icon in home screen and styled bottom navigation view
- [X] Style the feed to look like the real Instagram feed.
- [ ] User can load more posts once he or she reaches the bottom of the feed using infinite scrolling.
- [ ] Show the username and creation time for each post.
- [ ] User can tap a post to view post details, including timestamp and caption.
- [ ] User Profiles
      - [ ] Allow the logged in user to add a profile photo
      - [ ] Display the profile photo with each post
      - [ ] Tapping on a post's username or profile photo goes to that user's profile page and shows a grid view of the user's posts 
- [ ] User can comment on a post and see all comments for each post in the post details screen.
- [ ] User can like a post and see number of likes for each post in the post details screen.


## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/maria-jpg/Parstagram/blob/master/Walkthrough2.gif' title='Video Walkthrough for Parstagram pt.2' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

As I was walking through the videos, I would often stumble across import errors or errors from deprecated methods. Luckily it was solved
when I looked at a few Android Studio documentation. 
Another place I found myself stuck in was making sure the icons were aligned properly. Often some of the icons or buttons were too big or small for the implementation. 

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Maria Palomino]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

--------------------------------------------------------------------------------------------------------------------------------------------------------
# Project 3 - *Parstagram*

**Parstagram** is a photo sharing app similar to Instagram but using Parse as its backend.

Time spent: **6** hours spent in total

## User Stories

The following **required** functionality is completed:

- [X] User can sign up to create a new account using Parse authentication.
- [X] User can log in and log out of his or her account.
- [X] The current signed in user is persisted across app restarts.
- [X] User can take a photo, add a caption, and post it to "Instagram".

The following **optional** features are implemented:

- [ ] User sees app icon in home screen and styled bottom navigation view
- [ ] Style the feed to look like the real Instagram feed.
- [ ] After the user submits a new post, show an indeterminate progress bar while the post is being uploaded to Parse.

The following **additional** features are implemented:

- [X] Giving an Instagram feel to the log-in and sign-up

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/maria-jpg/Parstagram/blob/master/Walkthrough.gif' title='Parstagram Walkthrough' width='' alt='Parse App Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

A challenge I encountered while creating this application was when I was changing activites and adding click listeners to my buttons. It turns out that I needed to also
add these new activities into my AndroidManifest.xml! The changes worked eventually.

## Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [2021] [Maria Palomino]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
