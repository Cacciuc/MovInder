# MovInder

The Idea is from some 9Gag post and lucienperouze wanted to start it, but it doesnt seem that he started it.

Let's do it all toghether!

Naming Ideas welcome!!!

### idea
Swipe on movies.
Choose another user, with whom you want to watch a movie with and see all the matches.
Or swipe with all the common likes to choose a movie with this specific partner (add a few of the most liked movies too, even if it has no common likes, as long as it has no dislikes)

#### Maybe later:
Click on a movie and choose the streaming service to open the corresponding app with the right movie selected. (need to find out wether most apps allow URI routing)
Possibility to choose for a movie, that you do not want to watch it again or not to watch it again with a specific user

## Frontend
Frontend will be done with Xamarin.Forms, so that we only need to make the app once for Android and iOS.


## Backend
Backend is still open for ideas. (Maybe Express)

### Database setup:
Movie table: MovieId primary, name, description, image
Category table: CategoryId primary, name
Movie-Category match table: Id primary, CategoryId, MovieId 
User table: UserId primary, username, e-mail, passwordHash, salt
User-Movie match table: Id primary, UserId, MovieId, like/dislike

