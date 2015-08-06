# CSGO-Scoreboard
CSGO Odense Tournament Scoreboard

```json
{
    "match": {
        "match_id": int,
        "match_title": string,
        "map": string,
        "round": int,
        "teams": [team]
    },

    "team": {
        "team_id": int,
        "team_name": string,
        "rounds_won": int,
        "players": [player]
    },

    "player": {
        "player_id": int,
        "player_name": string,
        "score": [K/D/A]
    }
}
```