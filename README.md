# Social Web Portal/ Application on GAE using GAE datastore

Its a Group Project

#### GAE URL: https://rock-perigee-274822.uc.r.appspot.com/

#### Facebook URL: https://apps.facebook.com/531280837764071

#### Description

1)FbGaeDataStoreServlet.java

FbGaeDataStoreServlet is to handle creating new tweets to add to the GAE -doGet method is to create a new "tweet" entity and add it to the GAE Datastore -GAEDatstore is an instance of the DatastoreService interface that provides synchronous access to the GAE Datastore
To create a new tweet entity message to add to the Datastore -To create cookies for the application user's user_id, first name, last name, and profile picture and add them to the client response -To add the new tweet entity message repo to the datastore associated with the GCP project and maintain the returned key for the new tweet entity in the tweet_key variable
to get tweet id from datastore

2)friends.jsp

-this is to handle Friends part of application - like view all friends tweets -To create a table to display all of friends tweets -To display the friends tweets if the request contains the proper parameter -To create a DatastoreService interface instance -To create a new query for entities whose kind is "tweet" and sort the query results -To loop through all of the tweet entity results and display the entities whose user_id field doesn't match the user_id of the current user -To Increment the visited_count field for each friends tweet

3) LinkedTweet.jsp
-this is to fetch linked tweet from DataStore and display the tweet content

4)topTweets.jsp
-This is to handle the Top Tweets section of the application -To create a query that sorts the tweets in descending order based on their visited count -To iterate through the sorted tweets to get 10 most popular tweets

5)tweet.jsp
-This handles the Tweet section of the application -To Create a table to display all of user's tweet messages -To Delete a tweet as necessary if the correct parameter exists before displaying all of the user's tweets in the Datastore
