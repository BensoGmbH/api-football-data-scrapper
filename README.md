# api-football-data-scrapper

The api-football-data-scrapper reads data from the https://v3.football.api-sports.io REST api and stores the data in another repository 

```
     ┌────────────────────────────┐
     │                            │
┌────►        api-sports.io       │
│    │                            │
│    └────────────────────────────┘
│
│    ┌────────────────────────────┐
│    │                            │
└────┤ api-football-data-scrapper │
     │                            │
     └──────────────┬─────────────┘
                    │
     ┌──────────────▼─────────────┐
     │                            │
┌────►   data-store-repository    │
│    │                            │
│    └────────────────────────────┘
│
│    ┌────────────────────────────┐
│    │                            │
└────┤      video-generator       │
     │                            │
     └────────────────────────────┘



```