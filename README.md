OnPlayerFly
===========

## Credits ##
* [Y_Less](http://forum.sa-mp.com/member.php?u=29176) and [IpSBruno](http://forum.sa-mp.com/member.php?u=87608): Hook Method 7
* [pds2k12](http://forum.sa-mp.com/member.php?u=178953): Developing the script.
* * [[uL]Pottus](http://forum.sa-mp.com/member.php?u=169807): For the GetPlayerVelocity idea.
* [Emmet_](http://forum.sa-mp.com/member.php?u=73154): Testing the include with me.
* [SouthClaw](http://forum.sa-mp.com/member.php?u=50199):  For the array of all the water places around San Andreas

## Callback ##

	public OnPlayerFly( playerid )
	{
		Ban(playerid);
		SendClientMessage(playerid, -1, "You have been banned for fly hacking.");
		return true;
	}

