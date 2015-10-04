the finalproduct.html file is the basic setup with the Indicio 
IO setup. While its currently displaying this information as a webpage,
it has enough functions to pass in a block of text, along with a positive or
negetive sentiment, and repeatedly generate updated profile for the user,
which contains keywords that they like and dislike. This could be used to check
if a user would like a certain peice of text. We imagine this being applied to news
articles or perhaps things displayed on facebook.

Currently the setup is somewhat clunky to work arround something we encountered with the 
response speed of the Indicio ajax call. In order to use the html file and see it in action,
simply select like or dislike, enter a level of detail (the number of keywords to be queried for)
a block of text, and then click the buttons in the following order.
1. Analyze Text
2. LOG DATA
3. Parse and Display

Note: Top 5 least like are not yet implemented, and there are some bugs with the top 5 most liked.
Looking at the chrome console output can however show the accurate paths.

Secondary Note: I'll be entirely honest, this could use some more work, like saving the embeded profile in a cookie, or signing it with a public key, then embedding it for recovery later. I'm just very tired at this point, so sorry for any spelling errors in this readme.

