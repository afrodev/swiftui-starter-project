# swiftui-starter-project
Jesus and Humberto started project

This project is to have discussions about iOS platform and study Swift UI.

## The first lesson
1. Do an App that have a list of albums with image. 
To do that you can use the api: https://jsonplaceholder.typicode.com/albums
It returns a json with all the albums available. 

**Business Rules:**
- You need to show the albums titles.
- You need to get the `albumId` because you will need in the next screen.

2. After tap in one of the album images you will go to a detail screen. This screen will need to show information from this API: https://jsonplaceholder.typicode.com/photos?id={id_of_album}

**Business Rules:**
- You need to show the albums photos (`thumbnailUrl`), album title, image title.


The design following [Apple Guidelines of list on Swift UI](https://developer.apple.com/design/human-interface-guidelines/components/layout-and-organization/lists-and-tables/). You can try to follow all the guidelines but you can use your criativity to do all of that.


It's is preferrable to split what you need to do in small tasks and open PRs for each of them.
Example: 
1. Prepare to map data from webservice.
2. Create webservice consumer
3. Creating view model
4. Fix problem from X


Use it Swift UI, it will be good if you use the new API for async await too (optional).
Any doubt just send me a message.
