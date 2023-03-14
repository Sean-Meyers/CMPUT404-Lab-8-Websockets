# nodejs-ws-lab

University of Alberta, CMPUT 404 Lab 8 starter repository. Create a basic Phaser
game with WebSocket connectivity for real time server to client communication.

## Quickstart

1. Clone this repository.
    * `git clone https://github.com/uofa-cmput404/nodejs-ws-lab.git`
2. Change the working directory into this directory
    * `cd nodejs-ws-lab`
3. Install the node dependencies.
    * `npm install`
4. Start the application.
    * `npm start`

Application should be up at [http://localhost:8080](http://localhost:8080).


**Question 1:** What do you see in the browser? When you open another tab and perform a click/drag action, what happens?
- I see a bunny, and when I open another tap and move the bunny, the other bunny moves too, and fast. Magic.

**Question 2:** What are some of the differences between TypeScript and JavaScript?
- TypeScript transpiles into JavaScript. Adds type safety.

**Question 3:** Why is a web application bundler (Parcel, Webpack, Rollup, etc.) useful for modern web projects? What are some features that [ParcelJS](https://parceljs.org/) provides?
- Bundles all the modules and code together into 1 or 2 files, so they can be downloaded in one go by webapp users.
- allows faster loading

**Question 4:** What are the different values for the readyState a WebSocket can be in? Briefly describe what each state means. (Hint: check out the [Mozilla WebSocket API](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket))
- 0: CONNECTING: "Socket has been created. The connection is not yet open." I guess this means that we're currently establishing a connection, but not done yet, so we have to wait until it's done to use it.
- 1: OPEN: We are now receptive to what the other party is saying. Listening mode.
- 2: CLOSING: We are desperately trying to wrap up the conversation without being awkward or rude.
- 3: CLOSED: Thank goodness we can no longer hear the other party's blabbering.

**Question 5:** What's the link to your github repo?
- https://github.com/Sean-Meyers/CMPUT404-Lab-8-Websockets/tree/topdown