# Privacy Policy

Movie Meter works only specific movie-related pages - this list is always available in the extension Popup / Show introduction page.

Only on these pages, extension will try to extract IMDb ID, movie name, movie year and video type (movie or TV show).  
Only this information - IMDb id, movie name, movie year, video type - is then send to the cloud server (hosted at "https://movies.fastaddons.com" domain) to fetch information about the movie.

If returned video type is "TV show", then another remote request is being made to "https://api.tvmaze.com" domain, to fetch information about previous and next episode.  
This request always contains only the "IMDb ID" of the TV show.

In both cases, no user-sensitive or user specific data are ever send.  

All data send to my server "movies.fastaddons.com" are only used to identify the Movie and return info about it. They are not stored.
