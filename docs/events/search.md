# Events Search

Search for event with home/away name plus date

## HTTP Request

`GET https://api.betsapi.com/v1/events/search`

> curl "https://api.betsapi.com/v1/events/search?token=YOUR_TOKEN&sport_id=1&home=Man%20City&away=Barcelona&time=1478029500"

### URL Parameters

Parameter | Required? | Description
--------- | ------- | -----------
sport_id | Yes | [Reference](#sport_id)
home | Yes | home team ID or name
away | Yes | away team ID or name
time | Yes | either UTC time epoch (Limited to 90 days) or day YYYYMMDD

## HTTP Response

<a href="../samples/search.json" target="_blank">search.json</a>
