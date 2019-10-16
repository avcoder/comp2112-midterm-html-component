	
# Purpose: 
Take an existing HTML template of twitter profiles and allow the user to click on each one in order to see more details and to tweet

## Emulate this
https://www.youtube.com/watch?v=qGhP6N-xywc&feature=youtu.be&hd=1

# What you'll need:

- Download attached midterm-twitter.zip which contains .html, .css, .js files
- Ensure CSS framework from  https://tachyons.io/ should already be included in the html file
- The html template for each twitter short-profile is found here:  https://tachyons.io/components/lists/follower-notifications/index.html  (scroll down its page to copy html)
- The html template for each twitter long-profile is found here:  https://github.com/avcoder/comp2112-midterm-html-component/blob/master/README.md#long-profile-twitter 
- The html template for each tweet is found here:  https://github.com/avcoder/comp2112-midterm-html-component/blob/master/README.md#tweet
- API to use is from  https://randomuser.me/documentation#multiple
- feel free to add id's, classes, data-attributes

# Goals (1% per goal achieved).  Using the techniques you've learned in this class, do the following:

1. Using the API (see above), fetch 3 twitter short-profiles such that upon refresh, a random set of three short-profiles is always fetched (may use fetch, or async/await/fetch, but not XMLHttpRequest)
1. Display all the people using the short-profile HTML template (see above)
1. Make the Add User button functional such that it fetches one more person (may use fetch, or async/await/fetch, but not XMLHttpRequest) ...
1. ...then displays that additional person to the end of the short-profiles list 
1. If user clicks one of the short-profiles, the long-profile for that clicked-person displays instead along with a textarea box and a Tweet button
1. Ensure long-profile shows details such as email, cell, and location/state
1. If user types something in the textarea boxes and clicks tweet, then display that tweet using the tweets HTML template (see above) 
1. Any prior tweets will already show and any new tweets are simply added to the list of prior tweets
1. If user goes back to short-profiles list, and clicks another person, user can similarly create tweets for that person as well
1. Make the Go Back button functional such that it appears whenever a long-profile is displayed; upon click, displays the short-profiles list


Submit: zip file via Blackboard of all your files
