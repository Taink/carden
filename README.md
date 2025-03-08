# carden
A card game lobby manager

> This program is a work in progress. You probably can't use it in its current state.

## Features

This is the current feature roadmap for a "1.0" version:

- Create "lobbies" that can be joined by other people with an URL or code
- Manipulate one or multiple virtual decks of playing cards, that is:
  - Deal hands to each player
  - Shuffle the cards
  - As a player, draw individual cards from a deck or other players' hands
- Try to prevent cheating by holding the game's full state on the server only,
  and share to the players only the data required to display their own "view" of the game's state

This will require a frontend and a backend.
I don't really want to host this anywhere for a long time,
so I'll try to make it as portable/self-contained as possible.
I'm still on the fence as to which languages I'll be using for the backend,
so I will probably write a simple web frontend
that can display a game's state and go from there.

While designing the backend,
I'll try to make it so it can be used with any kind of frontend:
a web UI, a GUI desktop/mobile application, a TUI...

For the sake of debugging and because of its ubiquity,
I'll probably exchange data in JSON between the client(s) and the server.
I will also probably need some form of Javascript for user interaction in the frontend,
and websockets to make the client-server updates "real time".

## Why does this exist?

I'm currently (at the time of writing) unemployed and looking for work.
While actually searching for a job is important,
I think that maintaining and fostering my programming skills is also important (if not more!).

So on the side of my job search, I've been improving my skills.
One of the ways I've done this is going through
[boot.dev](https://www.boot.dev/)'s backend developer curriculum.
This is my ["Personal Project 1"](https://www.boot.dev/courses/build-personal-project-1).

Here's my profile if you're interested: <https://www.boot.dev/u/taink>.
I think it's private though; I don't really like sharing my personal information online if I can avoid it.
If you want to reach me, you can do so at this address:
`taink-contact.oxidizing119@passmail.net`.

As for why I chose this particular project idea, at the time of writing this,
it seems feasible within the 20-40 hours time frame of the assignment,
while remaining pretty interesting and (possibly) challenging in some ways.
The features scope is fairly open-ended and if I finish what I'm setting to do here "too quickly",
I can easily add more features to the mix, or improve the frontend.

Also, I like playing card games.
I remember playing Tabletop Simulator and thinking its basic functionality was pretty cool.
One could view this project as a simpler version of Tabletop Simulator.
