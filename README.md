# joke-teller
### Description: 
This app has a button which when clicked tells a joke to the user. It has a simple UI with a background gif and a button.
The project uses [_Mozilla’s experimental Web Speech Synthesis API_](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis).
It also uses [JokeAPI v2](https://rapidapi.com/Sv443/api/jokeapi-v2/) to get random jokes.
A joke fetched from the joke API is then supplied to the text-to-speech engine of the Web Speech Synthesis API which converts the text to audio format
and plays it in a natural voice.
This app’s UI is mobile-friendly but the text-to-speech function **MAY NOT WORK ON MOBILE DEVICES** due to browser limitations.
The gif is taken from [Giphy](https://giphy.com/) courtesy [Biteable](https://giphy.com/search/biteable).
