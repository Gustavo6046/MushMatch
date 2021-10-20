# 1.3.1 Changelog

 * Force zero frag limit, and warn if a different value is set in config
 * Fix the majority of settings; there was no way to set those through INI files
 * Have bot attitude always be "ignorant" on match start, never engaging other players
 * Change 'immune-resistance' parameter update and make it also configurable.
 * Slight rebalance to default bot AI suspicion radius values
 * Fix premature ending in network games
 * Fix Beacon firerate setting replication
 * Fix Sporifier being put down for players in netgames
 * Fix tiny-damage AI suspicion culling
 * Make Sporifier not have mush owner spotted if it's in the put down animation
 * Make chance-based suspicion checks repeat per witness
 * Add suspicion overlook chance modifiers for mush-witness-human-instigator, and witness-is-victim, situations