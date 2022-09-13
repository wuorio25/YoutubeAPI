This code: Queries 50 random videos (in no order) from your channel using YouTube's Data API

Displays the duration of the video that was picked from the array store and displays (in milliseconds) in the console.

Renders the chosen video to the DOM using div id=player and player = new YT.Player('player', {}

Uses YouTube's onYouTubeIframeAPIReady iframe API for event handling.

Will wait for the end of the random video, and will then refresh the page and repeat.

Make sure to update API_KEY and CHANNEL_KEY with your own ChannelID and API KEY

Instructions on how to setup API Key: https://developers.google.com/youtube/v3/getting-started

Instructions on how to find Youtube Channel ID: https://support.google.com/youtube/answer/3250431?hl=en
