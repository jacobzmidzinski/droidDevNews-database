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
    "8-droidConNYC2020": {
        "logo": "https://firebasestorage.googleapis.com/v0/b/mobile-development-272712.appspot.com/o/images%2FdroidConNYC.png?alt=media&token=66b77e2a-3101-4d2d-ad22-c44955040559",
        "endDate": {
            "_seconds": 1605657600
        },
        "url": "nyc.droidcon.com",
        "startDate": {
            "_seconds": 1605571200
        },
        "city": "New York",
        "country": "United States of America",
        "name": ".droidCon NYC",
        "coordinates": {
            "_latitude": 40.7281787,
            "_longitude": -73.9600141
        },
        "tags": ["tickets", "CFP"]
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
