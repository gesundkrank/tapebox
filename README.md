# tapebox

tapebox will allow you to create mixtapes on your server and share them with your friends.

## Idea
The central idea is to allow people share music with their friends. Without piggyback on services like Youtube, 
Spotify or Soundcloud and their limited offer. A self hosted service that makes a box of mixtapes out of your server. 
But they will also come with the limitations of a classic mixtapes. No skipping. No direct selection of tracks. 

## Planned features

- Upload and tag music files
- Create mixtapes from uploaded files
- By default mixtapes are shared with nobody
- Allow multiple ways of sharing: login, link?

## API

The tapebox API must provide at least the following functionalities:
- Restful
- Simple authentification and access restriction
- Upload and tagging of music files (a.k.a. titles)
    - Tags: name, interpret, album, personal comment 
- Delete/edit of uploaded files 
- Create/edit/delete mixtapes (Should at least have a id and name)
- Add/Remove titles to/from mixtapes
- Share mixtapes

API documentation in the [wiki](https://github.com/gesundkrank/tapebox/wiki/tapebox-API).