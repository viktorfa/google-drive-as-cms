# google-drive-as-cms

Each file and folder on Google drive has an ID. The [Google Drive REST API](https://developers.google.com/drive/v3/web/about-sdk) lets you get a file or files in a folder with a HTTP request. An unauthorized request can get all public files. So just make a folder public in Google Drive and get the ID of the folder from the sharing link (everyone with link can view).
I suggest editing files in Google Drive with [Stackedit](https://stackedit.io/) which is a markdown editor with Google Drive integration. The markdown files can easily be rendered in a static website. 


[https://developers.google.com/drive/v3/web/about-sdk](https://developers.google.com/drive/v3/web/about-sdk)  
[https://developers.google.com/drive/v3/web/search-parameters](https://developers.google.com/drive/v3/web/search-parameters)


More structured data can also be accessed from Google Drive Sheets and its own api.
