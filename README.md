<b>Chat Bot Messenger Based on OpenAI APi</b>

Advanced Chatbot based on GPT an openai project

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Changelogs](#changelogs)
- [Credits](#credits)
- [License](#license)

## Installation

Linux/Windows: Use nodejs v15 up.
No need to install modules, required modules are already installed.
<br>
Get your fb login cookie and paste it inside session.json

`git clone https://github.com/suff3r1ng/messenger-openai.git`
<br>
`cd messenger-openai`
<br>
`node execute.js`
<br>

## Usage

Functions:<br>

`/help - show list of commands to trigger the bot`<br>
`/forecast 'iNPUT CITY NAME'- show weather forecast.`<br>
`/weather 'INPUT CITY NAME'- show current weather`<br>
`/img 'ANY COMMANDS eg. image of a pug'- Generate an image`<br>
`/ai 'YOUR QUESTION'- Ask the AI gpt-3.5-turbo-0301  `<br>
`/stop - Stop`<br>
`/continue - continue the ai`<br>

## Changelogs:

Added weather.<br>
Added image generator.<br>
Updated to model gpt-3.5-turbo-0301.<br>
Added Message History of up to 10 messages only to save tokens for the api.<br>

## Credits

- [FB api.](https://github.com/Schmavery/facebook-chat-api/)

- [Openai api.](https://openai.com)

## License

- [GNU](https://www.gnu.org/licenses/gpl-3.0.en.html)

_*suff3r1ng*_