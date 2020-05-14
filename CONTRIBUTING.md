![droidDevNews](./featureGraphic.png)

# How to contribute?

## Commit message template / Pull request title

Commit messages or pull request titles should look like so: **Method Subject: Title**

- Method: **Add, Update** or **Delete**
- Subject: **News, Event** or **Contributor**
- Title: E.g. title of the article or name of the event

## News

##### JSON template
```
{
    "1-firebaseTeamAnnouncesKotlinExtensions": {
        "tags": ["firebase", "ktx"],
        "title": "Firebase Kotlin Extensions are out of Beta! ",
        "curator": {
            "name": "Jacob Zmidzinski",
            "url": "https://jacobzmidzinski.com"
        },
        "publishDate": {
            "_seconds": 1586476822,
            "_nanoseconds": 300000000
        },
        "contentType": "article",
        "description": "Firebase Team announced that Firebase Kotlin Extensions are out of Beta!",
        "url": "https://firebase.googleblog.com/2020/03/firebase-kotlin-ga.html"
    }
}
```

##### News Tags

* **android**
* **firebase**
* **google developers**
* **kotlin**
* **ktx**
* **lifestyle**
* **podcast**

##### News Content Type

* **article**, means that link redirects user to article
* **podcast**, means that link redirects user to podcast
* **video**, means that link redirects user to e.g. YouTube video
* **meetup**, means that link redirects user to meetup sign-up page
* **online_meetup**, means that link redirects user to online meetup sign-up page

## Events

##### JSON template
```
{
    "16-droidConSanFrancisco2020": {
        "websiteUrl": "https://sf.droidcon.com",
        "twitterUrl": "https://twitter.com/droidconsf",
        "startDate": {
            "_seconds": 1607904000
        },
        "city": "San Francisco",
        "country": "USA",
        "venueName": "Mission Bay Conference Center",
        "name": ".droidcon San Francisco",
        "coordinates": {
            "_latitude": 37.7678058,
            "_longitude": -122.3933172
        },
        "tags": ["tickets", "cfp"],
        "logo": "https://firebasestorage.googleapis.com/v0/b/mobile-development-272712.appspot.com/o/images%2FdroidConSanFrancisco.png?alt=media&token=1c6d2b87-3b0f-4c7a-b246-74d11752faaa",
        "endDate": {
            "_seconds": 1607990400
        }
    }
}
```

##### Events Tags

* **tickets**, means that tickets are available for purchase
* **online**, means that event takes place online

## Contributors

##### JSON template
```
{
    "jacobZmidzinski": {
        "name": "Jacob Zmidzinski",
        "url": "https://firebase.googleblog.com/2020/03/firebase-kotlin-ga.html"
    }
}
```
