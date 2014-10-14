hackathons-api
==============

A public API that provides upcomming hackathons based on data from Twitter, Facebook, Eventbrite, etc.

####Example

```
GET hackathonsapi.com/hackathons?limit=15&offset=0

{
  data: [
    {
      id: 'f43fwfw3r4w3de'
      name: 'SalesForce 1Millon Hackathon',
      source: 'twitter.com/salesforce'
    },
    ...
  ],
  total: 1500
}
```
