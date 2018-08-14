# fixcrasherforcaypen
Crasher Fix 0.3e by Maxim_Zuev

new CheckSobeit[10];
	
GetPlayerVersion(playerid, CheckSobeit, sizeof CheckSobeit);
	
if(strfind(CheckSobeit, "LoL4" ) != -1) 
  return SendClientMessage(playerid, 0xFF4530FF, "У вас установлен собейт, удалите и тогда вы сможете играть у нас"), Kick(playerid);
