# DcNotify for FINAL FANTASY XIV
A Dalamud plugin to send a Discord Webhook Message to your Server whenever a Party Finder event or duty pop happens with an AFK client.

This is a fork of [PushyFinder](https://github.com/lostkagamine/PushyFinder) that uses Discord as an alternative to Pushover for sending/receiving notifications.

Credit to [@lostkagamine](https://github.com/lostkagamine/) for the original idea and implementation.

## Usage

### Discord Setup
1. Go to your Text Channel where you want to receive notifications.
2. Go to settings and click on `Integrations`.
3. Click on `Create Webhook`.
4. Copy the Webhook URL

### In Game
Configure the plugin in game using `/dcn` command.  
  - Enter the ***Webhook Url*** you copied before. 
  - Can toggle the following options.
      - Send messages for duty pop
      - Ignore AFK status and always notify
