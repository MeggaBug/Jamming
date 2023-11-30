# **Jamming**
Uses Spotify API to build a website that allows users to search the Spotify library, create a custom playlist, then save it to their Spotify account.

![Jamming](https://static-assets.codecademy.com/Courses/react/projects/previews/jamming-project-four-three-preview.gif)

### Technologies used  
- HTML
- CSS
- JavaScript
- React
- HTTP Requests and Responses
- Authentication

### Project Requirements
- Build a web app using React
- Version control the application with Git and host the repository on GitHub
- Integrate with Spotify or another API
- Deploy your application

### Features 
- Spotify Login — the first time a user searches for a song, album, or artist, Spotify will ask them to log in or set up a new account. ??
- Search by Song, Album, or Artist — a user can type the name of a song, artist, or album into the search bar and click the SEARCH button.
- Populate Results List — Jammming displays the list of returned tracks from the user’s query.
- Add Song to a Custom Playlist — users can add a track to their playlist by selecting a + sign on the right side of the track’s display container. ??
- Remove Song from Custom Playlist — users can remove a track from their playlist by selecting a - sign on the right side of the track’s display container. ??
- Change Playlist Title — users can change the title of their custom playlist. ??
- Save Playlist to Account — users can save their custom playlist by clicking a button called SAVE TO SPOTIFY.

### Potential improvements
- Pressing enter triggers a search
- Include preview samples for each track
- Only display songs not currently present in the playlist in the search results
- Add a loading screen while playlist is saving
- Update the access token logic to expire at exactly the right time
- After user redirect on login, restoring the search term from before the redirect
Ensure playlist information doesn’t get cleared if a user has to refresh their access token
