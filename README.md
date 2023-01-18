# ⚙ Await of The Planets
Request all planets from all pages https://swapi.boom.dev/api/planets and visualize them as boxes on the page

Requirements
The project must run when started via npm run start
The first request must not have a page query parameter.
There must be a property named _loading defined in Application.js which is a < progress > element
There must be a method named _load defined in Application.js
There must be a method named _create defined in Application.js
There must be a method named _startLoading defined in Application.js
There must be a method named _stopLoading defined in Application.js
Fetch must be used inside of the _load method
Await must be used inside of the _load method
The _load method must be async
All planets must be visualized as boxes on the page
The loading bar must be visible while making the requests
The loading bar must hide when the requests are completed
The first request URL must be /planets instead of /planets?page=1
Gotchas
Use the already defined progressbar on the page
Move the rendering of the boxes inside of the _create method

🤯💥💣
