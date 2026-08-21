**** FR ****
0/ Requiert Stream Deck 7.1 or later (menu ☰ → About) et Windows 10/11
1/ installer Runtime .NET 8 : winget install Microsoft.DotNet.Runtime.8
2/ importer le plugin (double click io.github.nounns.helldivers.streamDeckPlugin) 
3/ (optionnel, permet d'avoir des icones du jeu) copier pack dans %APPDATA%\Elgato\StreamDeck\Plugins\io.github.nounns.helldivers.sdPlugin\static\imgs\ 
4/ relancer streamdeck (click droit quitter dans la zone de notification)
5/ dans le volet droit, un menu Helldiver 2 apparait avec un icone stratagème à faire glisser dans le profile streamdeck
	Titre : le texte qui s'affichera sur l'icone
	Stratagème : le stratagème souhaité
	Nom : laisser vide
	Code : à personnaliser si nécessaire mais les stratagème embarque déjà les codes
	Recharges :  à personnaliser si nécessaire mais les stratagème embarque déjà les colldown
	Touche stratageme : pour choisir la trouche ingame

INFO générale : 

Appui bref : envoie le code et lance le compte a rebours. 
Appui long : remet le compteur a zero (utile si le stratageme n'a pas ete lance).

Good to know : 

Le jeu ne communique rien : le compte a rebours est une estimation qui demarre a l'appui, alors que la recharge reelle demarre a l'explosion de la balise. Les temps des prereglages changent a chaque patch — le champ Recharge permet de les corriger. Le jeu doit etre configure en mode APPUI (et non maintien) pour la touche stratageme.

**** EN ****
0/ Requires Windows 10/11 and Stream Deck 7.1 or later (menu ☰ → About)
1/ Install the .NET 8 Runtime: winget install Microsoft.DotNet.Runtime.8
2/ Import the plugin (double-click io.github.nounns.helldivers.streamDeckPlugin)
3/ (Optional, gives you in-game style icons) copy the "pack" folder into
   %APPDATA%\Elgato\StreamDeck\Plugins\io.github.nounns.helldivers.sdPlugin\static\imgs\
4/ Restart Stream Deck (right-click the notification tray icon, then Quit)
5/ A "Helldivers 2" category appears in the right-hand panel, with a Stratagem
   action to drag onto your Stream Deck profile
	Title: the text shown on the key
	Stratagem: pick the one you want
	Name: leave empty
	Code: only if you need to override it — presets already include the codes
	Cooldown: only if you need to override it — presets already include the cooldowns
	Stratagem key: the in-game key you use to open the stratagem menu

GENERAL:
Short press: sends the code and starts the countdown.
Long press: resets the countdown (handy when the stratagem wasn't actually thrown).

GOOD TO KNOW:
The game doesn't expose any data, so the countdown is only an estimate: it starts
when you press the key, whereas the real cooldown starts when the beacon detonates.
Preset cooldowns change with every patch — use the Cooldown field to correct them.
The game must be set to PRESS mode (not hold) for the stratagem key.
