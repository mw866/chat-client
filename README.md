# Chat Client 
A web client for group chats on desktop browsers based on [SendBird JavaScript Web Basic Sample](https://github.com/sendbird/SendBird-JavaScript/tree/master/web-basic-sample).

The client supports open channels, group channels, and read receipts using  [SendBird  JavaScript SDK](https://github.com/sendbird/SendBird-SDK-JavaScript) and [Express](https://expressjs.com/).

## Demo

The demo client is available at https://chat-client.chriswang.tech/


## Getting Started
1. Install packages

> Require that you have Node v8.x+ installed. 

```bash
npm install
```

2. Build

```
npm build
```

3. Run

```bash
npm start
```

## Customizing the sample
If you want to put some changes into the sample, you should build it using `webpack`.  

1. Install packages

> Require that you have Node v8.x+ installed. 

```bash
npm install
```

2. Modify files
If you want to change `APP_ID`, change `APP_ID` in `./src/js/const.js` to the other `APP_ID` you want.  
You can test the sample with local server by running the following command.  

```bash
npm run start:dev
```

3. Build the sample
When the modification is complete, you'll need to bundle the file using `webpack`. The bundled files are created in the `dist` folder. 
Please check `webpack.config.js` for settings.    

```bash
npm run build
```
