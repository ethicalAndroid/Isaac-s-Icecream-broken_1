	-- Icecream Cone 001
  if (cacheFlags == CacheFlag.CACHE_SPEED) then
		if player:HasCollectible(icyMod.COLLECTIBLE_ICECREAM_CONE) then
			if icyMod.Has001 == "Nope" then
				icyMod.FruityFlavor = "Yup";
				icyMod.Has001 = "Yup";
				player.MoveSpeed = player.MoveSpeed + 0.3;	
				-- debug_text = "got item 001";
	end end end
  	
    -- Pure Vanilla 003
	if (cacheFlags == CacheFlag.CACHE_LUCK and CacheFlag.CACHE_SPEED) then	
		if player:HasCollectible(icyMod.COLLECTIBLE_PURE_VANILLA) then
			if icyMod.Has003 == "Nope" then
				icyMod.Has003 = "Yup";
				icyMod.VanillaFlavor = "Yup";
				player.MoveSpeed = player.MoveSpeed + 0.2;
				player.Luck = player.Luck + 1;
				-- debug_text = "got item 003";
	end end end
