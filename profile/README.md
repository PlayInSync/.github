### <p align='center'><b>Play <i>offline</i> videos in Sync across the internet.</b> </p>

### How?

Everytime someone changes the state of video playback (play/pause, seek, playback speed) the client sends that information to the server, and the server stores them, when all other clients connected to the same server request for changes the server sends those updates it stored previously and the clients update their playback state according to the data recieved.

### Why?

Since all clients have the video required to sync even before the sync starts, this removes the hassel of streaming video (which leads to loss in quality and drop in fps)

For client see - https://github.com/PlayInSync/PlayInSync-Client

For server see - https://github.com/PlayInSync/PlayInSync-Server

# Server

# 🛠️ Installation & Set Up

##### 1. Clone the repo

```sh
git clone https://github.com/PlayInSync/PlayInSync-Client
```

##### 2. Install packages

```sh
npm i
```

##### 3. Run index.js using node

```sh
npm start
```

##### 4. Expose it to the Internet.

By default the app will listen to port 3000 and localhost, expose that to the internet to be able to use it from anywhere.

# 💻 Technologies used

- TypeScript
- Express

# Client

### 🛠️ Installation & Set Up

##### 1. Clone the repo

```sh
git clone https://github.com/PlayInSync/PlayInSync-Client
```

##### 2. The site is completely static, no need for a local server, just open **index.html**

<img width="100%" src="https://raw.githubusercontent.com/PlayInSync/PlayInSync-Client/main/media/index.jpg" alt="index.jpg">

##### 3. Put in the [server](https://github.com/PlayInSync/PlayInSync-Server) URL

<img width="100%" src="https://raw.githubusercontent.com/PlayInSync/PlayInSync-Client/main/media/connect.jpg" alt="index.jpg">

##### 4. Choose the video to play, Click **Sync**

<img width="100%" src="https://raw.githubusercontent.com/PlayInSync/PlayInSync-Client/main/media/pick.jpg" alt="index.jpg">
<img width="100%" src="https://raw.githubusercontent.com/PlayInSync/PlayInSync-Client/main/media/sync.jpg" alt="index.jpg">

##### 5. Enjoy

<img width="100%" src="https://raw.githubusercontent.com/PlayInSync/PlayInSync-Client/main/media/enjoy.jpg" alt="index.jpg">

# 💻 Technologies used

- TypeScript

# Might add later (idk)

- [ ] Ability to create rooms in the same server
- [ ] Somekind of permission system

# Contributing

- Fork the repo
- Work on a different branch
- Make changes
- Create a pull request
