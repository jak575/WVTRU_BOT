WVTRU Bot
================
A bot for automating WVTRU transactions on the Vitruveo blockchain.
Getting Started
---------------
To use this bot, you'll need to configure your Vitruveo wallet credentials and other settings. Here's a step-by-step guide to get you started:
You'll find a file named .env_example in the same directory as the bot executable. Rename this file to .env.
### 2. Add your Vitruveo wallet credentials to the .env.yml file
**IMPORTANT**: Before proceeding, please make sure you understand the importance of keeping your private key safe. **DO NOT** use your main wallet's private key with this bot. Instead, create a new wallet specifically for this purpose and fund it with the amount of VTRU you wish to wrap.
Open the newly renamed .env file and add your Vitruveo wallet credentials. You'll need to add the following variables:
* KEY: Your Vitruveo wallet private key (from the new wallet you created)
* VALUE: The amount of VTRU to wrap
Here's an example of what the .env file should look like:

 #### PRIVATE_KEYS:
    - your_vitruveo_private_key_here 
    - key 2
    - key 3
 #### VALUE: 100

*If you only want to run 1 key, only have 1 line of keys*
> Replace **your_vitruveo_private_key_here** with your actual **Vitruveo wallet private key**.
>> AGAIN, PLEASE MAKE SURE TO KEEP YOUR PRIVATE KEY SAFE. DO NOT SHARE IT WITH ANYONE. IF YOU LOSE YOUR PRIVATE KEY, YOU WILL LOSE ACCESS TO YOUR FUNDS.
### 3. Save the .env.yml file
Once you've added your credentials to the .env.yml file, save it and close the file.
### 4. Run the bot
You can now run the bot by simply clicking on the executable file (WVTRU_Bot.exe). The bot will start running and will automatically send WVTRU transactions based on the settings in your .env file.
* Note: Selling is not supported at this time.
* You can also run multiple instances of the bot.
## Notes
-----
* **Important**: Make sure to keep your .env file secure and do not share it with anyone. * Make sure to enter the correct private key and value in the .env file to avoid any errors.
> **Important Disclaimer**: Please be aware that there is a 3% tax for using this bot. This means that 3% of the VTRU you wrap will be deducted as a fee. By using this bot, you acknowledge that you have read and understood the terms and conditions.