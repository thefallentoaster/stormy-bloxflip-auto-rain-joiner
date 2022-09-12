# Stormy

- my discord: https://discord.gg/XBcaXJejFQ
- credits to: https://github.com/amprocode/Bloxflip-auto-rain-joiner  

## Stormy v1.4
- added captcha solving api

## Stormy v1.3
- added guided setup and auto cashout

## Stormy 1.2
- fixed some bugs

## Stormy 1.1
- fixed some bugs

## Stormy v1.0:
- added new features and uploaded to Github


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Information:
- When there is a rain at [bloxflip](https://bloxflip.com) this program will join the rain and let you know some information about it
- It also have's a few more funktions like auto withdraw, status notifier and rain notifier!

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Installation:
1) download the latest version of the program
2) Extract the files to a foler of your choice
3) run the **"install.bat"** file and it should start running
4) get an free licence on my discord


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Notes:
- Best If Ran Overnight or on a another unused pc on the side.
- Tip: It also works on my Raspberry Pi but the instalation of the requirement take 2-3 hours!
- Usually generates 50-60 Robux a day.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Config guide:

Default config.json file:
```json
{
  "minimum_amount": 100,
  "amount_to_withdraw_automatically": 0,
  "refresh_rate": 20,
  "mouse_movement": "True",
  "autowithdraw_enabled": "False",
  "webhook_enabled": "True",
  "webhook_ping": "<@everyone>",
  "webhook": "https://discord.com/xxxxxxxxxxxxxx",
  "webhookbalance": "https://discord.com/xxxxxxxxxxxxxx",
  "webhookwithdraw": "https://discord.com/xxxxxxxxxxxxxx",
  "webhookannounce": "https://discord.com/xxxxxxxxxxxxxx",
  "authorization": "authtoken"
}
```
### minimum_amount:
Minimum rain amount intended for the program


### amount_to_withdraw_automatically
Amount to withdraw automatically


### refresh_rate:
How often you want it to check if there is a rain


### mouse_movement:
If set to "True" it will move your mouse This helps get past botfail

### autowithdraw_enabled:
Here you can toggle the auto withdraw function, if you want it set it to "True"

### webhook_enabled:
Should be obvious but if you want the rain notifier to send a message to your discord webhook set it to "True"


### webhook:
If you set webhook_enabled to "True" input your webhook into here to it can actually send it to you. Create for all webhooks an seperate channel or you will end up in an chaos



### authorization:
This is your bloxflip login token, this is used to get your username and robloxid.

- To get this head to [bloxflip](https://bloxflip.com).
- Next press the "F12" key on your keyboard or "CTRL + SHIFT + I"
- Now make sure "console" is selected, if not just click on it (image attached)



- Next paste in the code below
```
copy(localStorage.getItem('_DO_NOT_SHARE_BLOXFLIP_TOKEN'))
```
- You should now have your bloxflip token copied to your clipboard, just open your config file and paste it inbetween the quotation marks.

## Current Issues:
- Bot takes his time for starting the status message after joining rain. It takes up to 10 minutes.
- You have to update all .png files for the auto cashout (if you enabled it) in the assets folder for you screen resolution. 
