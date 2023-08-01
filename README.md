# Memory Game 🧠

An entertaining Memory Game featuring two playful puzzles – numbers and icons. Enjoy this amusing game with 1 to 4 players, featuring both 4x4 and 6x6 grid challenges. Match hidden icons or numbers to win the game. Try it out now and test your memory skills!

Click [here](https://memory-game-rajeev.vercel.app/) and Enjoy the Memory game.

<p align="center">  
<img src="./public/preview.png"/>  
</p>

## Features and Interfaces

1. Home page

   - Player can select the type of game between Icon and Number.
   - Player can select the number of players.
   - Single user can play game with computer logic.
   - 4x4 and 6x6 grid challenges to make game more entertaining.

2. Game Page

   - A grid of cards with hidden icons or numbers.
   - A timer to show the time taken by the user to complete the game.
   - A counter to show the total moves taken by the user to complete the game.
   - A button to go back to home page.

   - A button to restart the game.

   - ![image](./public/preview2.png)

3. Winner Page

   - A Greet message to the winner.
   - Time taken by the user to complete the game.
   - Total moves taken by the user to complete the game.
   - A button to play again.
   - A button to go back to home page.

   - ![image](./public/preview3.png)

## Tech stack

#### Frontend

- React.Js
- JavaScript
- React-DOM
- User Events
- Redux

#### Other Tools

- Font Awesome/react-fontawesome
- Fort Awesome/free-solid-svg-icons

## Points to remember while testing the app

1. First setup the backend by following instructions in this [repository](https://github.com/prathamesh-mutkure/anti-cheat-app-backend)
2. When testing on android emulator, if you get a connection error use `http://10.0.2.2/` instead of `localhost`
3. iOS emulator doesn't support camera, this will give an error, use a real device to test AI features.
4. On real devices, make sure your PC and mobile are connected to same network, use network IP address instead of `localhost`
5. Don't forgot the `PORT` number
6. Allow **permissions** for camera and mic when asked
7. Make sure the `BACKEND_URL` is appended with `/api`

## Instructions

1. Import the project through Android Studio or clone it
   - `https://github.com/prathamesh-mutkure/anti-cheat-exam-app.git`
2. Install flutter packages
   - `flutter pub get`
3. Generate store classes
   - `flutter packages pub run build_runner build`
4. Create a `.env` file and set the following variables
   - `BACKEND_URL`
5. Connect your device or emulator and run the app
   - `flutter run`
6. The app is now running

## Useful Links

- [Project Demo](https://memory-game-rajeev.vercel.app/) for Web version

- [Project Repository](https://github.com/Rajeevjewar/Memory-Game.git)

## Need help?

Feel free to contact me on [Twitter](https://twitter.com/RajeevKumar504) or [LinkedIn](https://www.linkedin.com/in/rajeevkumar504/), know more about me at [iamrajeev.me](https://iamrajeev.me)

[![Twitter](https://img.shields.io/badge/Twitter-follow-blue.svg?logo=twitter&logoColor=white)](https://twitter.com/RajeevKumar504)
