## Discord ScreenShare Bot

Updated version that im trying to get working.

### Setup
Create an `.env` file with the following content:

```
token=
owner_id=
log_channel_id=
```

Create a discord user, find the token and set it in .env `token`

If you don't set `owner_id` anyone can use the bot or else only you and the people you add can control it

Join the selfbot user to your guild and type `*help`, If it respond your bot is working.

### Run

```
sudo docker build .
```

### Note (`owner_id`)
Use the following commands to add or remove other users
```
*add `user_id`
*remove `user_id`
```

You can also use `*list` to see added users.

### Contributing
Pull requests are welcome