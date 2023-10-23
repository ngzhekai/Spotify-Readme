<div align="center">
  <img src="spotify.svg" width="100" align="center">
  <h1>Spotify Readme</h1>
</div>

<p align="center">
  A dynamic, customizable, and real-time Spotify now-playing widget for your README files. If you're not currently playing a song, it'll display one of your recent songs! </p>

## Customization Previews

<p>
  Just add query parameters to the endpoint, there are many possible combinations! (If you're on mobile and your screen is small, please use a desktop browser or change the zoom level to zoom out)
</p>

| Parameter | Default | Values          |
| :-------- | :------ | :-------------- |
| `spin`    | `false` | `false`, `true` |
| `scan`    | `false` | `false`, `true` |
| `theme`   | `light` | `light`, `dark` |
| `rainbow` | `false` | `false`, `true` |

#### Default

```
/api
```

![Preview](https://spotify-readme-ngzhekai.vercel.app/api)

#### Spinning CD Effect

```
/api?spin=true
```

![Preview](https://spotify-readme-ngzhekai.vercel.app/api?spin=true)

#### Include Scan Code

```
/api?scan=true
```

![Preview](https://spotify-readme-ngzhekai.vercel.app/api?scan=true)

#### Rainbow Equalizer

```
/api?rainbow=true
```

![Preview](https://spotify-readme-ngzhekai.vercel.app/api?rainbow=true)

#### Dark Theme

```
/api?theme=dark
```

![Preview](https://spotify-readme-ngzhekai.vercel.app/api?theme=dark)

## Notes (Disclaimer)

This is a forked repo from [tthn0's project](https://github.com/tthn0/Spotify-Readme). I have made some minor changes for my use case, which is able to be viewed on small screen.

## Setup guide from the original author

The setup is slightly different from the original. Please refer to <a href="https://github.com/novatorem/novatorem/blob/master/SetUp.md">this page</a> for the setup, but take notice of these differences:

-   Use the <code>/api</code> endpoint as opposed to <code>/api/spotify</code>
-   The environment variables are different:
    -   `SPOTIFY_CLIENT_ID` ➠ `CLIENT_ID`
    -   `SPOTIFY_SECRET_ID` ➠ `CLIENT_SECRET`
    -   `SPOTIFY_REFRESH_TOKEN` ➠ `REFRESH_TOKEN`
