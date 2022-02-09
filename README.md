# lordle

lordle is an Android focused version of [powerlanguage's](https://www.powerlanguage.co.uk/) game *[Wordle](https://www.powerlanguage.co.uk/wordle)*. Most of the code written by  a brilliant [lynn]() who also goes by [@chordbug]() on Twitter. Check out their repo in the sidebar if you want to really learn how this game works!

<img src="https://i.imgur.com/oVLf4Aj.png" alt="drawing" width="400"/>

## Added Features
* Since this is mostly revolved around being a copy of Wordle that doesn't reuire internet, games are shared by seed instead of by http link. When results are shared they dipaly as such:

```bash
Lordle c2xpbmc 6/6

🟩⬛⬛⬛⬛
🟩⬛🟩🟨⬛
🟩🟩🟩⬛⬛
🟩🟩🟩⬛⬛
🟩🟩🟩🟩⬛
🟩🟩🟩🟩🟩
```
&nbsp; So that the seed, and number of attempts are clearly displayed as well as an emoji progress graph, which for some reasons most clones don't 
&nbsp; &nbsp; have!
* You can copy the seed alone at any point in the game by pressing 'Copy current seed to clipboard'.
* You can 'Give up' and see the anser to your prompt, or roll with a new word entirely by clicking 'New word (will clear game)'.


## Installation

Use the package manager [npm](https://www.npmjs.com/) to install lordle.

```bash
npm run start
```
to run a development build, or 
```bash
npm run build
```
to run a production build.

## Android Export
[This](https://medium.com/@christof.thalmann/convert-angular-project-to-android-apk-in-10-steps-c49e2fddd29) tutorial by [Christof Thalmann](https://medium.com/@christof.thalmann) explains the process of converting Node.JS, Angular, etc. to an apk using [cordova](https://cordova.apache.org/). An app-debug.apk is available out-of-the-box located at ***.\platforms\android\app\build\outputs\apk\debug***

Otherwise a version of the apk will be included in Releases.

## License
View license at the link below!
[MIT](https://choosealicense.com/licenses/mit/)

## Contact Me!
You can contact me at [@lukevoyer](https://twitter.com/lukevoyer) on Twitter or e-mail me at [lukevoyer1@gmail.com](mailto:lukevoyer1@gmail.com)
