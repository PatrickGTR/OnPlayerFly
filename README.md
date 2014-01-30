OnPlayerFly
===========

This include was created by pds2k12, thanks to [uL]Pottus for the idea to check the players velocity and thanks to Emmet_ for helping me with ALS_ and testing the include.

## Callback ##

	public OnPlayerFly( playerid )
	{
		Ban(playerid);
		SendClientMessage(playerid, -1, "You have been banned for fly hacking.");
		return true;
	}

