# PKMN-SV-Egg-collector

Pokemon SV - Egg Collector (MicroController only)

# Features:
- Checks eggs every 1m30s, checking takes 30s meaning a cycle is 2m
- checks as if it has 9 eggs
- Auto Sandwich maker
- Does 12 cycles before re-making sandwich
- Closes dialogue so you don't get stuck and not generate eggs (this may mess up, idk why, currently finding a way to make it more consistent
- Whistle cancels whenever pressing B so you don't accidentally crouch (crouch glitch was a bit inconsistent and crouching wont allow you to interact with basket)
- Estimated an average of 45 eggs per 30m or 90 eggs per hour (SLOW AF compared to swsh)

I made this bc I don't have a full setup nor a pc I can casually leave on standby alongside my switch whenever I want to run a PA program
This only needs an arduino, plug in on the change grip controller menu like past programs and you're good to go

# PLEASE DON'T FORGET TO SCAN IT w/ antivirus always for precaution.

As I am doing this project alone, please dm/ping me at Niffy#4428 if you find a bug/error... so I can fix it, if you have a video of said error even better 
 
 
 
# Instructions
 
Starting position: 
 
 ![alt text](https://cdn.discordapp.com/attachments/711649658220314635/1051105482011590726/IMG_20221208_105154.jpg)
 
Connect arduino at change grip menu

![alt text](https://cdn.discordapp.com/attachments/750184046448869429/1051127261039960134/IMG_20221210_205703.jpg)

If you want to set a custom time, change this specific line in the .C file with notepad++ or something and then compile

12 = 30m
24 = 1h
36 = 1h30m
48 = 2h 

and so on.

![alt text](https://cdn.discordapp.com/attachments/711649658220314635/1051109582879080530/Screenshot_3.jpg)

## Thanks & Credits
[Progmem](https://github.com/progmem/Switch-Fightstick) (Switch-Fighstick internal)

[Shinyquagsire23](https://github.com/shinyquagsire23/Switch-Fightstick) (Switch-Fighstick internal)

[BrianuuuSonic](https://www.youtube.com/user/brianuuusonic2) (Base programs for swsh that I reverse engineered)

[Split](https://github.com/spl-t/swsh-auto-host) (Showed me how to RE)

Bgoproton & Svatinus (Initial testers)
