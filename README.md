# ACNH Pocket Guide App Website
Just a fun little website written to creatively advertise my ACNH Pocket Guide app I wrote in React Native.

The website is hosted at https://acnh-pocket.web.app/

## Deploy to Firebase
Run the following command in the root project folder to deploy to firebase

```> firebase deploy```

## To deploy to all Firebase alias sites
Edit ```firebase.json``` adding ```"site": "acnh-pocket",``` under ```"hosting"```

For example:
```
{
  "hosting": {
    "public": "public",
    "site": "acnh-pocket",
    "ignore": [
      "firebase.json",
      "**/.*",
      "**/node_modules/**"
    ]
  }
}
```

Repeat for all hosting firebase domains:
* ```acnh-pocket```
* ```acnh-pocket-guide-app```
* ```acnh-pocketguide```
* ```animal-crossing```