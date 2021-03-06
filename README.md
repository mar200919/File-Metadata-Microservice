# Author
![@mar200919](https://avatars0.githubusercontent.com/u/11713907?s=460&v=4)

Created by mar200919

[Github](https://github.com/mar200919) | [FreeCodeCamp](http://www.freecodecamp.com/mar200919) | [CodePen](https://codepen.io/mar200919/)

# FreeCodeCamp API: File Metadata Microservice
## User stories:
1. I can submit a FormData object that includes a file upload.
2. When I submit something, I will receive the file size in bytes within the JSON response

**Hint:** You may want to use this package: https://www.npmjs.com/package/multer

## Example query usage:

Upload file from the UI at the root.
```text
https://file-metadata-r282.herokuapp.com
```

## Example query output:

```text
https://file-metadata-r282.herokuapp.com/upload
```

```js
{
"name": "2016-01-26.png",
"size": 258957,
"date": "1/27/2016, 1:30:52 AM",
"file": "1453858252196.png"
}
```

The information displayed is all the information that is stored in a database. The files then gets deleted rigth away.
In the future, uploading the cloud could be implemented and then with the database the files could be retrieved using a get, this is not yet implemented and not in any futures plans to be.
