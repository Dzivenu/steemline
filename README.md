# SteemLine

Multifeed, Statistics and Notifications for Steem!

# Planned Features

- Notifications for incoming votes, replies and mentions
- Follow/Unfollow
- Scheduled Posting
- Uploading images
- Voting Bot
- Profile/Follow Popups on usernames (also mentions in posts/comments)

# Known Bugs

- Sometimes the connection to steem can't be esteblished it seems.
- Sometimes the animations and line sorting are broken or break on the go.
- After up- or unvoting the vote state changes and flips back again once `updateAccount` is called (10 sec interval).
- After up- or unvoting the voting box of all posts opens on hover
- Clicking the upvote button of a post far to the right (last 3 or sth.) the slider will scroll back to the first post on the left.
- Unfocussing the vote percentage dropdown makes the slider scroll right.
- Dragging doesn't work correclty in firefox.
- ...