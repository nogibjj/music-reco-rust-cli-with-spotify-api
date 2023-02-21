# A music recommendation cli tool using Rust with Spotify Developer API 

## Usage

### 1. Obtain a "client id" and a "client secret" from [Spotify developer website](https://developer.spotify.com/dashboard/applications)

- Learn ways to [generate the access token](https://github.com/mianwu515/rust-world-spr23/tree/main/music-recommendation-service-with-spotify-api#steps) with the client_id and client_secret

### 2. Run the CLI tool with your ready client_id and client_secret
`cargo run -- music --genre [NAME of the GENRE] --id [YOUR ACCOUNT ID] --secret [YOUR ACCOUNT SECRET]`

For example, `cargo run -- music --genre acoustic --id 123456xxx --secret abcdefxxx`

Possible genres can be found below.

### 3. Example output
```text
Rock House Boogie by John Lee Hooker
Nobody Knows You When You're Down and Out - 78rpm Version by Bessie Smith
Sweet Little Angel by B.B. King
Mr. Highway Man by Howlin' Wolf
She Caught the Katy and Left Me a Mule to Ride by Taj Mahal
Blue Ridge Mountains by Fleet Foxes
Try (Just a Little Bit Harder) by Janis Joplin
Nine Below Zero - Live by Muddy Waters
Wall of Denial by Stevie Ray Vaughan
Sharp Dressed Man - 2008 Remaster by ZZ Top
Sitting On Top Of The World by Howlin' Wolf
I'd Rather Go Blind by Joe Bonamassa
Tears in Heaven by Eric Clapton
At Last - Single Version by Etta James
Playin' With My Friends by B.B. King
Angel of Mercy - Single Version by Albert King
Help Me by Sonny Boy Williamson II
Lonely Avenue - 2005 Remaster by Ray Charles
The Lady Is A Tramp - from the Hootenanny 2008 by Jools Holland & Lily Rose Cooper (née Lily Allen)
'Tain't Nobody's Bizness If I Do by Bessie Smith
```

### 4. Possible genres from Spotify API as of Feb 20, 2023
```bash
{
  "genres": [
    "acoustic",
    "afrobeat",
    "alt-rock",
    "alternative",
    "ambient",
    "anime",
    "black-metal",
    "bluegrass",
    "blues",
    "bossanova",
    "brazil",
    "breakbeat",
    "british",
    "cantopop",
    "chicago-house",
    "children",
    "chill",
    "classical",
    "club",
    "comedy",
    "country",
    "dance",
    "dancehall",
    "death-metal",
    "deep-house",
    "detroit-techno",
    "disco",
    "disney",
    "drum-and-bass",
    "dub",
    "dubstep",
    "edm",
    "electro",
    "electronic",
    "emo",
    "folk",
    "forro",
    "french",
    "funk",
    "garage",
    "german",
    "gospel",
    "goth",
    "grindcore",
    "groove",
    "grunge",
    "guitar",
    "happy",
    "hard-rock",
    "hardcore",
    "hardstyle",
    "heavy-metal",
    "hip-hop",
    "holidays",
    "honky-tonk",
    "house",
    "idm",
    "indian",
    "indie",
    "indie-pop",
    "industrial",
    "iranian",
    "j-dance",
    "j-idol",
    "j-pop",
    "j-rock",
    "jazz",
    "k-pop",
    "kids",
    "latin",
    "latino",
    "malay",
    "mandopop",
    "metal",
    "metal-misc",
    "metalcore",
    "minimal-techno",
    "movies",
    "mpb",
    "new-age",
    "new-release",
    "opera",
    "pagode",
    "party",
    "philippines-opm",
    "piano",
    "pop",
    "pop-film",
    "post-dubstep",
    "power-pop",
    "progressive-house",
    "psych-rock",
    "punk",
    "punk-rock",
    "r-n-b",
    "rainy-day",
    "reggae",
    "reggaeton",
    "road-trip",
    "rock",
    "rock-n-roll",
    "rockabilly",
    "romance",
    "sad",
    "salsa",
    "samba",
    "sertanejo",
    "show-tunes",
    "singer-songwriter",
    "ska",
    "sleep",
    "songwriter",
    "soul",
    "soundtracks",
    "spanish",
    "study",
    "summer",
    "swedish",
    "synth-pop",
    "tango",
    "techno",
    "trance",
    "trip-hop",
    "turkish",
    "work-out",
    "world-music"
  ]
}
```
## References

* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
