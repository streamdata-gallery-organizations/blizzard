---
swagger: "2.0"
x-collection-name: Blizzard
x-complete: 0
info:
  title: World of Warcraft Get Realm Status
  description: Retrieves realms status information. This information is limited to
    whether or not the realm is up, the type and state of the realm and the current
    population.
  version: 1.0.0
host: us.battle.net
basePath: /api/wow/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /character/{realm}/{characterName}:
    get:
      summary: Get Character Realm Charactername
      description: Fetches a single character at a time through an HTTP GET request
        to a URL describing the character profile resource. By default, a basic dataset
        will be returned and with each request and zero or more additional fields
        can be retrieved. The core dataset returned includes the character's realm,
        name, level, last modified timestamp, thumbnail, race id, achievement points
        value, gender id and class id.
      operationId: getCharacterRealmCharactername
      x-api-path-slug: characterrealmcharactername-get
      parameters:
      - in: path
        name: characterName
        description: The character name
      - in: query
        name: fields
        description: Indicates that one or more of the optional datasets is to be
          retrieved
      - in: path
        name: realm
        description: The realm name
      responses:
        200:
          description: OK
      tags:
      - Character
      - Realm
      - CharacterName
  /guild/{realm}/{guildName}:
    get:
      summary: Get Guild Realm Guildname
      description: Fetches a single guild at a time through an HTTP GET request to
        a url describing the guild profile resource. By default, a basic dataset will
        be returned and with each request and zero or more additional fields can be
        retrieved. The core dataset returned includes the guild's name, level, faction
        and achievement points.
      operationId: getGuildRealmGuildname
      x-api-path-slug: guildrealmguildname-get
      parameters:
      - in: query
        name: fields
        description: Indicates that one or more of the optional datasets is to be
          retrieved
      - in: path
        name: guildName
        description: The guild name
      - in: path
        name: realm
        description: The realm name
      responses:
        200:
          description: OK
      tags:
      - Guild
      - Realm
      - GuildName
  /realm/status:
    get:
      summary: Get Realm Status
      description: Retrieves realms status information. This information is limited
        to whether or not the realm is up, the type and state of the realm and the
        current population.
      operationId: getRealmStatus
      x-api-path-slug: realmstatus-get
      responses:
        200:
          description: OK
      tags:
      - Realm
      - Status
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---