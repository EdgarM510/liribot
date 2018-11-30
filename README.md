# LiriBot
**The command line node app**
[Youtube video demo](https://youtu.be/x4Ugetbe5vo)


### Summary
**Liri** is a command line application written in NodeJS. It can be used to search for information about **movies**, **songs**, and upcoming **concerts**. Liri uses **NodeJS**, **DotEnv**, **Moment**, **Axios**, **Node-Spotify-API**, **OMDB API**, and **Bands In Town API**. Liri logs all previously inputed commands in the `log.txt` file.


### Usage
While in the directory of **liri.js**, use the command line to type a search term as follows:

(example)
`node liri movie-this toy story`

First type **node liri**
then type an **operator**
your choices are:
* concert-this
* spotify-this-song
* movie-this
* do-what-it-says

finally type a **search term**


### Requirements
LiriBot uses **NodeJS** and the following npm packages:
*DotEnv
*Moment
*Axios
*Node-Spotify-API

You will need a `.env` file with this content
```
# Spotify API keys

SPOTIFY_ID=your-spotify-id
SPOTIFY_SECRET=your-spoitfy-secret


# Bands in town App ID

BANDSINTOWN_ID=your-bands-in-town-id


# OMDB key

OMDB_KEY=your-omdb-key
```
