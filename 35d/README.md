
[Cheat Engine](http://cheatengine.org/) table files for Sub Rosa Alpha 35d.

# Server notes

S3 mod provides following custom admin commands:

``` 
Player arguments are typed in as either substring of the name (case sensitive, e.g. "Tony" for Tony Montana), or full phone number without the dash ("2561234"), or the last part of the phone number ("1234" for 256-1234)

/s3sync - reload the files listing teams and participants
/s3mode 0 - return to normal
/s3mode 1 - S3 Round mode (Phase 2)
/s3mode 2 - Racing mode (Phase 1) 
/s3mode 3 - NOT IMPLEMENTED
/s3mode 4 - Gun Game (Phase 4.1)
/s3mode 5 - Versus (Phase 4.2) 
/s3mode 6 - NOT IMPLEMENTED

/rg - alias for /resetgame
/skip - set timer to 00:01
/lock - toggle timer lock
/mv player, team - move player to another team
/op player - make player an admin
/rn player,new_name - rename player
/pre player,tag - give tag to the player (e.g. "/pre Tony,[A] ")
/shift - rotate the 3 teams
/kill player - kill the player ingame
/ready - force ready up everyone
/setcash player,amount - set cash and nullify stocks
/putgun player,gun - put a gun with 7 mags and a bandage into save-state inventory in case someone leaves and rejoins between 4.1 and 4.2 (overwritten on round reset!!)
/car type,color

misc:
/pos - display coordinates
/bot - spawn a dummy bot
/arm_all gun,mags - e.g. /arm_all 11,3   works in racing!
```

# IDs

```

Teams

0 - Goldmen Inc.
1 - Monsota
2 - OXS International
3 - Nexaco
4 - Pentacom
5 - Team 6
6 - Bots
7 - Civilian

Items

00  0 Auto 5
01  1 AK-47
02  2 AK-47 Magazine
03  3 M-16
04  4 M-16 Magazine
05  5 Magnum
06  6 .45 Bullets
07  7 MP5
08  8 MP5 Magazine
09  9 Uzi
0a 10 Uzi Magazine
0b 11 9mm
0c 12 9mm Magazine
0d 13 Grenade
0e 14 Bandage
0f 15 Briefcase
10 16 Open Briefcase
11 17 Cash
12 18 Cash
13 19 Black disk
14 20 Green disk
15 21 Blue disk
16 22 White disk
17 23 Gold disk
18 24 Red disk
19 25 Cell Phone
1a 26 Key
1b 27 Door
1c 28 Newspaper
1d 29 Burger
1e 30 Desk
1f 31 Lamp
20 32 Pay Phone
21 33 Memo
22 34 Soccer Ball
23 35 Rope


Vehicles

00  0 Town Car
01  1 Town Car 2
02  2 Metro
03  3 Limo
04  4 Turbo
05  5 Turbo S
06  6 Beamer
07  7 Van
08  8 Minivan
09  9 Truck
0a 10 Trailer
0b 11 Heli
0c 12 Train
0d 13 (Train engine)
0e 14 Hatchback
0f 15 Test

```
