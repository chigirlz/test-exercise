# ➿ Demo Tape


  1. Try your hand at the following exercise.

    This scripts in the starter directory send an SMS message containing the most popular track of an artist on Spotify.  

    Below is a list features for you to implement, including in-browser
    features which will require software to handle HTTP requests, perhaps using
    a web framework like Rails, Sinatra, Flask, Express, etc.

    As you add the following features, please use or replace the current
    implementation and test suite, adding new tests as you see fit and making
    commits with informative messages.

      1. Browser users should specify a artist and their phone number, then
         click a button to have the top track sent to them.

      2. Browser users should see a success message after they have clicked a
         button and successfully requested an SMS be sent _without the page
         reloading_.

      3. Implement a feature or improvement of your choosing. You're free to
         grab something from the icebox (see below) or devise another.

    The feature set of this app is minimal so that you can focus on aspects
    that you consider important for a robust production app built in
    collaboration with other developers.

  5. Deploy your app so that it is available via the internet.
     [Heroku](https://www.heroku.com) offers a free, easy to use platform for
     such things.


## Try to implement

- clean code
- TDD
- good architecture
- a robust, production-ready app
- an app ready for collaboration with other developers
- addressed possible security concerns
- small, atomic commits with concise messages

## Notes

There are some Spotify and Twilio credentials committed in the code. The Twilio
credentials [can't send real texts](https://www.twilio.com/docs/iam/test-credentials).
Feel free to use those credentials for this assignment, but set up your own
[free Twilio account](https://www.twilio.com/docs/usage/tutorials/how-to-use-your-free-trial-account)
to test with real credentials. *Please don't publically expose our (or your!) credentials.*

## Icebox

- Display artist info in the browser. Give it a cool layout.
- Embed the [play
  widget](https://developer.spotify.com/technologies/widgets/spotify-play-button/)
  and update it live as the user searches for different artists.
- Display links to album reviews in the single page app
- Popularity Trends. Which related group is most popular or increasing in
  popularity the quickest?
- Integration with TicketLeap. Does the artist have any upcoming concerts in
  the area?
