# GUM-iOS

Future Work:
Add Team Transferability and Team limits (This could be done through firebase possibly)
Currently it hardcoded for only Mark's email to be able to create teams.
This could be changed to add more emails, or ideally, make a admin section in the database to pull and check for admin emails. Of course ideally, once a user pays, their email will be added so they can make the team themselves.
Make longevity points actually do something
Make the streaks add to how many longevity points are given to the user after a video is completed.
Have streaks take the user to to the correct video. Currently just take the user to the start moving page.

Things to note:
The way we have implemented streaks is not ideal. The checks we have for the streaks do not accurately account for month switches. I'm sure there is a better way to implement this but we have not looked into it due to time limitations.
There are also some useless items currently, mainly the paypal button in the teams page is pretty useless as is.

Appstore Connect:
Builds must be uploaded to appstore connect before being pushed to the app store. You can watch a quick tutorial to figure it out exactly. For just beta testing go through testflight and make sure you are added to the testing group, and make sure that group is added to the build.
