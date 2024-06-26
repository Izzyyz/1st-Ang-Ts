# MMOG

## Description

#### MMOG is a page with all the MMO (Massive Multiplayer Online) games in which you will see around 400 games of the style with the respective information about it, a brief description of it with information such as the developers of the game for what type of platform they are. And the genre of games they are.

## Technologies Used

- VS Code: IDE Creative launchpad that you can use to edit, debug, and compile code.
- Node.js: Open source, cross-platform JavaScript runtime.
- Postman: Tool used to test APIs, allowing developers to send requests responses.
- Angular: Framework to create applications.

## External API Used

### MMO Games API - By MMOBomb

Access programmatically the best MMO games, multiplayer online games, news and giveaways! The MMO API (Powered by MMOBomb) is available for everyone to use without any restrictions. Please note our API is free to use as long as you attribute MMOBomb.com as the source of the data. We hope to improve the API over time.

Send us an email at contact@mmobomb.com if you find any bugs. Don't be afraid to experiment and feel free to share your projects with us.

#### Endpoints & Examples

Live games list
- GET https://www.mmobomb.com/api1/games

Games by platform
- GET https://www.mmobomb.com/api1/games?platform=pc

Games by category or tag
- GET https://www.mmobomb.com/api1/games?category=shooter

Sort games by release date, alphabetical or relevance
- GET https://www.mmobomb.com/api1/games?sort-by=alphabetical

Games by platform & category & sorted
- GET https://www.mmobomb.com/api1/games?platform=browser&category=mmorpg&sort-by=release-date

Filter Games by multiple tags for personalized results

- GET https://www.mmobomb.com/api1/filter?tag=3d.mmorpg.fantasy.pvp&platform=pc

Return details from a specific game
- GET https://www.mmobomb.com/api1/game?id=452


Live MMO Giveaways
- GET https://www.mmobomb.com/api1/giveaways

Latest MMO News
- GET https://www.mmobomb.com/api1/latestnews


### CORS Support
If you need cross-origin resource sharing features you can access our API via RapidApi at: rapidapi.com/digiwalls/api/mmo-games.
Rate Limits
 ### Please avoid doing more than 4 requests per second.
#### Responses
- 200: Success

- 404: Object not found: Game or endpoint not found

- 500: Something wrong on our end (unexpected server errors)

### All doc in https://www.mmobomb.com/api?ref=public_apis
