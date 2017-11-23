# Brumball
## A 6 player massively multiplayer pong game

Brumball was developed during [Brumhack 7.0](https://www.brumhack.co.uk/), a 24hr hackathon that was held in November 2017. It was developed by the Dysfunctional Programmers, a team of computer science students from University of Southampton.

## How can I run Brumball?
As Brumball was developed for a hackathon, it was very much intended to be used as a demo in a short presentation. Thus, it does not have a nice menu or start automatically. In fact, you need to press enter on the display in order to release balls. This can be changed by modifying game.js in /display.

Brumball consists of three components:

- Display
    - This is responsible for displaying the game
    - It handles all powerups and physics
    - Each display is unique as the random numbers are different.
    - Only one Display should be run per game.
- Server
    - This receives all the requests from the clients
    - Assigns clients to teams and handles disconnection
    - Gives nice numbers to the display on the position of the paddles
- Client
    - This is what the players will use on their phone to play
    - Sends data to the server

The display and client simply need to be hosted statically. The server needs to be run as Java with a port accessible by both the display and clients.

## Tweets
We got tweeted!

![Imgur](https://i.imgur.com/R1JLJls.png)
[Tweeted By MLH](https://twitter.com/MLHacks/status/932231486836789248)

![Imgur](https://i.imgur.com/nojYdDx.png)
[Tweeted By Capgemini](https://twitter.com/CapgeminiUKppl/status/932230984111706112)

## Photos
Below: The game running.
![MLH](https://i.imgur.com/EYyAsw5.jpg)
Below: Victory photo.
![MLH](https://i.imgur.com/8wbg5gr.jpg)

## Future Developments
We plan to fork this and develop it further. However, we will not be doing it here so that this repository documents our Hackathon.
