# BalancedPress

BlancedPress let's you see the political slant of an article. You can use it via our [chrome extention](bit.ly/balancepress) or our api. 

## API
To get the bias of an article send a get request to:

    GET http://balancedpress.herokuapp.com/v1/bias/?url=<YOUR_ARTICLE_URL>

## Contributers
David Lichtenberg [@dmlicht](https://github.com/dmlicht)  
Charles Leung [@LostMailman](https://github.com/LostMailman)  
Theresa Lee  
Steven Ko  

## Contributing
Think

## Under The Hood
When you send a request the the BalancedPress server, it will:
1. Download the webpage
2. Feed the text into a NLP model to calculate it's bias score
3. Return bias information and general article information to the client.

## Roadmap
1. Improve classification model
2. User bias report card
3. Linking articles with bias information included
4. Gamify it and compete with other friends on network to push people to read news from more objective sources.
