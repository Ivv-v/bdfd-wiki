# $playMusic
Play's music in Discord Voice Channel

## Syntax
```
$playMusic[Channel ID;Music Link;Volume]
```

### Parameters
- `Channel ID` `(Type: Snowflake || Flag: Required)` The channel to play music on.
- `Music Link` `(Type: String || Flag: Required)` The music to play.
- `Volume` `Type: Intenger || Flag: Optional)` The musics volume. Default: 70.

## Example
```
$nomention
Started playing music!
$playMusic[790875829018034186;https://www.youtube.com/watch?v=dQw4w9WgXcQ]
```

```discord yaml
- user_id: 803569638084313098
  username: RainbowKey
  color: "#E67E22"
  content: |
    !example
- user_id: 1009018156494368798
  username: BDFD Support
  color: "#378afa"
  bot: true
  verified: true
  content: |
    Started playing music!
- user_id: 803569638084313098
  username: RainbowKey
  color: "#E67E22"
  content: |
    You can now enjoy some music with your friends!
```
