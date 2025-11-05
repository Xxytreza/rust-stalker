# Rust Stalker Project


## Features:

 - Player Tracking with BattleMetrics and Rusticated:
 - - Add Player, Alert when is connected and disconnected
 - - If on rusticated can check if player died and killed

 - User stats tracking:
 - - total deaths, kills, etc... (Global use RustStats, idk if possible) 
 - - Kills, deaths, farm since wipe etc.. (PROBABLY ONLY ON RUSTICATED)
 
 - Green Rust integration (plants crossbreeding simulator)

 - Custom timed alerts (base decaying, time since last cargo etc... (If on Rusticated can be looked up))

 - Chatbot
 - - Can add player tracking, alerts etc...
 - - Probably shouldn't be hosted locally because performances in game (will probably be using huggingface)
 - - Knowledge about the game (raiding costs, etc...) (need to scrap wiki) (should be updated every month)
 - - Fast shortcut (alt + F10 for exemple or whatever)
 - - Server finder (Look on BattleMetrics with correct filters (probably pretty complicated))
 - - Using RAG will probably suffice 
