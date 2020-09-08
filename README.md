# Books-v2
![HTML,CSS Mockup Landingpage Books-v2](https://github.com/dianavile/Books-v2/blob/master/assets/img/Books-landingpage.PNG)

## Deployed Version
See deployed version on:
* [Github Page](https://dianavile.github.io/Books-v2/)
* [Netlify](https://jolly-elion-9e0c25.netlify.app/)

### Remember
There are two type of Paths: Absolute paths and relative paths.


#### 1) Absolute Paths 
- absolute paths ALWAYS INCLUDE DOMAINNAME of the website 
- with the (http(s) protocol: http:// or https://
```
http://www.site.com
https://www.site.com/assets/image.png
```

#### 2) Relative Paths
- relative links only point to a file or a file path.
The ROOT file = index.html. This is the point of departure.
From here all local files will be linked.

```
index.html
/assets/image.png
/css/main.css 
```
To include the correct file from the correct folder:
```
- ../foldername/filename.file-extension (=to connect to a URL in a file outside of index.html= OTHER LEVEL)
- /foldername/filename.file-extension (=to connect to a file in a folder on the SAME LEVEL).
- foldername/filename.file-extension (=to connect to a file directly, same LEVEL,same folder).
```
#### Source
- [Filepaths](https://www.w3schools.com/html/html_filepaths.asp)
