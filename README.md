# Athena Owl Discord Artificial Intelligence Bot 🤖
#### Your fledglings Robotic Owl Discord AI Companion!

## Features and commands 🌟

</details>

<details>
<summary><strong>Features ✨ (Click to expand) </strong></summary>

- [x] Mix of Slash and Regular Commands: You get the best of both worlds here! ⚙️
- [x] AI Image Generation: Bring your imagination to life for free! 🤖
- [x] Free Smart AI: Enjoy this capable language model at no cost to you. 🤖
- [x] Mention Notifications: The bot listens when you @ mention it. Like a friend ready to chat! ⚙️
- [x] Reply Handling: The bot knows who you're talking to, so it won't butt in confusingly. Pretty clever! 🪄
- [x] Channel Quiet Mode: Use /toggleactive so the bot chills in certain channels. ⚙️
- [x] GPT-3 Model: Harness advanced language tech like GPT-3. 🤖
- [x] Secure Credentials: We keep your login details safe behind the scenes. 🔑
- [x] Web Version: Check out the new web version for next-level features! 🌐
- [ ] YouTube Video Summaries: Coming soon! Get the key points from videos quickly. 🌐
- [ ] Voice Controls: Also coming soon - speak to control the bot with your voice!

</details>

<details>
<summary><strong>Commands ⚙️⚙️ (Click to expand) </strong></summary>

- [x] `/help`: See all the bot's abilities. ⚙️
- [x] `/pfp [image_url]`: Generate images with AI. 🖼️
- [x] `/imagine`: Give the bot a new nickname. 📛
- [x] `/changeusr [new_username]`: Change the bot's username. 📛
- [x] `/ping`: Get a friendly "Pong!" back. 🏓
- [x] `/toggleactive`: Turn the bot off in certain channels. 🔀
- [x] `/toggledm`: Toggle DM abilities on/off. 💬
- [x] `/clear`: Delete message history. 🗑️
- [x] `/gif`: See random cute/funny GIFs. 🐱
- [x] `/dalle`: Generate images with DALL-E AI.
- [x] `/support`: Questions? We're here to help!
</details>

## Additional configuration ⚙️

<details>
<summary><strong>Enabling Internet access 🌐🔍(Click to Expand)</strong></summary>

To ensure that the bot has access to the most up-to-date information, you can enable internet access by setting the `INTERNET_ACCESS` parameter to true in the `config.yml` file. This will allow the bot to retrieve information beyond the data it was initially trained on, which was only available up until 2021.

⚠️ You don't explicitly need to use the name `custom` for persona name and set it in `config.json` 
  
</details>

# Installation steps  🚩
### Step 1. 🎬 Git clone repository
```
git clone https://github.com/MrCargon/Athena_Owl_DiscordBot.git
```
### Step 2. 📁 Changing directory to cloned directory
```
cd Discord-AI-Chatbot
```
## Step 3. 💾 Install requirements
```
python3.10 -m pip install -r requirements.txt
```
### Step 4. 🔑 Getting discord bot token and enabling intents from [HERE](https://discord.com/developers/applications)
<details>
<summary><strong>Read more...  ⚠️  (Click to expand)</strong></summary>


##### Select [application](https://discord.com/developers/applications)
![image](https://user-images.githubusercontent.com/91066601/235554871-a5f98345-4197-4b55-91d7-1aef0d0680f0.png)

##### Enable intents
![image](https://user-images.githubusercontent.com/91066601/235555012-e8427bfe-cffc-4761-bbc0-d1467ca1ff4d.png)

##### Get the token !!! by clicking copy
![image](https://user-images.githubusercontent.com/91066601/235555065-6b51844d-dfbd-4b11-a14b-f65dd6de20d9.png)
</details>

### Step 5.Getting a Free Reverse OpenAI proxy Key 🔑

Follow these steps:

1. Join the Discord server by clicking on the following invite link: [NAGA AI](https://discord.naga.ac/)
2. Once you have joined the server, run the `/key get` command in any text channel.
3. This command will provide you with a reverse OpenAI key.

You can additionally enable `gpt-4` in `config.yml`

### Step 6. 🔐 Rename `example.env` to `.env` and put the Discord bot token and your Chimira gpt key It will look like this:
```
DISCORD_TOKEN=<YOUR_DISCORD_BOT_TOKEN
CHIMERA_GPT_KEY=<YOUR_CHIMIRA_API_KEY>
```
### Step 7. 🚀 Run the bot
```
python main.py
```
#### You may need to run as admin if you are on Windows
### Step 8. 🔗 Invite the bot 
You can Invite your bot using the link in console
![image](https://user-images.githubusercontent.com/91066601/236673317-64a1789c-f6b1-48d7-ba1b-dbb18e7d802a.png)

#### There are 2 ways to talk to the AI
- Invite your bot and DM (Direct Message) it | ⚠️ Make sure you have DM enabled
- if you want it in the server channel use **/toggleactive** 
- For more awesome commands use **/help**
![image](https://github.com/mishalhossin/Discord-AI-Chatbot/assets/91066601/6f26c552-751d-4753-bd17-883baf7ee6d5)