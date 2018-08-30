---
name: Blizzard
x-slug: blizzard
description: This is the documentation for the RESTful APIs exposed through the World
  of Warcraft community site as a service to the World of Warcraft community.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Blizzard
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/apis.md
specificationVersion: "0.14"
apis:
- name: World of Warcraft - Get Character Realm Charactername
  x-api-slug: characterrealmcharactername-get
  description: Fetches a single character at a time through an HTTP GET request to
    a URL describing the character profile resource. By default, a basic dataset will
    be returned and with each request and zero or more additional fields can be retrieved.
    The core dataset returned includes the character's realm, name, level, last modified
    timestamp, thumbnail, race id, achievement points value, gender id and class id.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/characterrealmcharactername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/characterrealmcharactername-get-openapi.md
- name: World of Warcraft - Get Guild Realm Guildname
  x-api-slug: guildrealmguildname-get
  description: Fetches a single guild at a time through an HTTP GET request to a url
    describing the guild profile resource. By default, a basic dataset will be returned
    and with each request and zero or more additional fields can be retrieved. The
    core dataset returned includes the guild's name, level, faction and achievement
    points.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/guildrealmguildname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/guildrealmguildname-get-openapi.md
- name: World of Warcraft - Get Realm Status
  x-api-slug: realmstatus-get
  description: Retrieves realms status information. This information is limited to
    whether or not the realm is up, the type and state of the realm and the current
    population.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/realmstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/realmstatus-get-openapi.md
- name: World of Warcraft - Get Auction Data Realm
  x-api-slug: auctiondatarealm-get
  description: Provides a per-realm list of recently generated auction house data
    dumps. The current auctions data is represented as JSON structures containing
    auction data for the tree auctions houses available on each realm.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/auctiondatarealm-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/auctiondatarealm-get-openapi.md
- name: World of Warcraft - Get Item Itemid
  x-api-slug: itemitemid-get
  description: Provides detailed item information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/itemitemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/itemitemid-get-openapi.md
- name: World of Warcraft - Get Arena Realm Teamsize Teamname
  x-api-slug: arenarealmteamsizeteamname-get
  description: Provides detailed arena team information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/arenarealmteamsizeteamname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/arenarealmteamsizeteamname-get-openapi.md
- name: World of Warcraft - Get Data Character Races
  x-api-slug: datacharacterraces-get
  description: Provides a list of character races.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/datacharacterraces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/datacharacterraces-get-openapi.md
- name: World of Warcraft - Get Data Character Classes
  x-api-slug: datacharacterclasses-get
  description: Provides a list of character classes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/datacharacterclasses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/datacharacterclasses-get-openapi.md
- name: World of Warcraft - Get Data Guild Rewards
  x-api-slug: dataguildrewards-get
  description: Provides a list of all guild rewards.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/dataguildrewards-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/dataguildrewards-get-openapi.md
- name: World of Warcraft - Get Data Guild Perks
  x-api-slug: dataguildperks-get
  description: Provides a list of all guild perks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/dataguildperks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/dataguildperks-get-openapi.md
- name: World of Warcraft - Get Data Item Classes
  x-api-slug: dataitemclasses-get
  description: Provides a list of item classes.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Blizzard_Entertainment_Logo.svg.png
  humanURL: http://battle.net
  baseURL: https://us.battle.net//api/wow/
  tags: APIs.io Import, Gaming, Stack, API Provider, Profiles, Relative Data, General
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/dataitemclasses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/blizzard/master/_listings/blizzard/dataitemclasses-get-openapi.md
x-common:
- type: x-api-json--authoritative
  url: http://apis.io/apisdef/legacy/blizzard.json
- type: x-api-gallery
  url: http://blazemeter.api.gallery.streamdata.io
- type: x-api-stack
  url: http://blizzard.stack.network
- type: x-developer
  url: https://dev.battle.net/
- type: x-github
  url: https://github.com/Blizzard
- type: x-twitter
  url: Blizzard_Ent
- type: x-website
  url: http://battle.net
- type: x-website
  url: https://www.blizzard.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---