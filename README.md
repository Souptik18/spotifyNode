## spotify clone app backend 🎧

#### Features of the app with UI description -

1. **Real time database storage persistent playing**

- All the details of the app are stored in realtime database using mongoDB for persistence

2. **Users after login can create playlist and queue songs in it**

- on the landing page click on create playlist after that list of available songs can be viewed select songs and give it a name on clicking on the custom playlist title under playlist and scroll down if the tracks bar is covering the create button click on the hamburger _i.e the three lined icon beside audio icon to the right_

- after creating the playlist play the songs from there
  click on the green play button below the playlist picture now to check if the tracks are on queue click on the forward button to check if the next song is queued 🎵

3. **Users can like the songs and artists from the app**

- from the created playlist like the playlist and like a song now check on the your library if the playlist is added

also check liked songs. 🎸

4. **preferences stored for personalized space**

- on user registration / login for the new user a music preferences picker is given to choose from the list of genres

- created playlist , liked artists, albums and also liked songs all in the your library for storing preferences real time

5. **Also the app comes with local login with backend as a service**

- mongoDB working in the background to store login information for the local login

6. **trending songs detection available**

- tested with 4 users on liking a particular music the song is detected as trending to the 5th user on registration

#### How to run the code?

1. _download the file as a zip and place it in a folder_
2. _open terminal and run npm install inside the parent folder of the app_
3. _open the mongodb server and paste the link "mongodb://localhost:27017/tracks" inside the connection string and click connect_ (check the env file for more details)
4. _in the terminal type npm run start_
5. now open the browser and type the port address given on the env file _example: localhost:3000_
#

🎶
Thank you !!

**Happy listening!!**

#
