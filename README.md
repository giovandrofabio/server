# NLW eSport - Trilha Ignite

Projeto construído do evento Next Level Week da RocketSeat

EndPoints
GET: http://localhost:3333/games/:GameID/ads
GET: http://localhost:3333/games/
GET: http://localhost:3333/ads/:GameID/discord
POST: http://localhost:3333/games/:GameID/ads
Body
{
    "name": "Giovandro",
    "yearsPlaying" : 2,
    "discord": "Giovandro",
    "weekDays": [0, 5, 6],
    "hourStart": "12:00",
    "hourEnd": "15:00",
    "useVoiceChannel": true
}