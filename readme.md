# Tank Box

The version of the GitHub repository is a re-engraved version of the classic tank battle, based on the original material, using React to encapsulate various materials into corresponding components. The material is rendered using SVG to show the pixel style of the game. You can adjust the browser zoom before playing the game. It is best to use 200% zoom under the 1080P screen. This game is developed using web front-end technology, mainly using React for page display, using Immutable.js as a data structure tool library, using redux to manage game state, and using redux-saga/little-saga to handle complex game logic.

### Development progress:

<details>
  <summary><b>Milestone 0.2 (completed on 2018-04-16)</b></summary>

- [x] The basic framework of the game
- [x] Single player mode
- [x] Exhibition page
- [x] Level editor and custom level management

</details><br>

<details>
  <summary><b>Milestone 0.3 (completed on 2018-11-03)</b></summary>

- [x] Performance optimization
- [x] Complete game sound effects (with some minor flaws)
- [x] Two-player mode (completed)

</details><br>

**Milestone 1.0（looks like a distant future /(ㄒ o ㄒ)/~~）**

- [ ] More reasonable computer players
- [ ] Complete design and development documentation
- [ ] Multiplayer game mode based on websocket

### Local development

1.  Clone the project to local
2.  Run  `yarn install` to install dependencies (or use `npm install`）
3.  Run  `yarn start` open webpack-dev-server, and open it in your browser `localhost:8080`
4.  Run  `yarn build` to pack the production version, packaged in output `dist/` folder

`devConfig.js` Contains some configuration items for development. Note that you need to restart webpack-dev-server after modifying the configuration in this file
