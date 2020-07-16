# csgo-server-configs

> CS:GO Server Configs for Competitive 5v5, Knife Round, Aim Map and FFA Deathmatch

Included in [`docker-csgo`](https://github.com/timche/docker-csgo).

## Download

Download the [latest release](https://github.com/timche/csgo-server-configs/releases/latest) and unzip in the `csgo` directory.

## Usage

Execute the configs on your server with `rcon exec <config>.cfg`.

### Example

```sh
rcon exec live.cfg
```

## Configs

### `live.cfg`

Config for a competitive 5v5 matches with default settings used in leagues and tournaments. Based on [ESL 5v5 server config](https://play.eslgaming.com/download/26251762/), but without the half time scoreboard bug.

### `knife.cfg`

Config for knife rounds with kevlar vest.

### `knife_taser.cfg`

Same as `knife.cfg`, but with taser.

Useful for knife rounds with a twist.

### `knife_he.cfg`

Same as `knife.cfg`, but with HE grenade.

Useful for knife rounds with a twist.

### `knife_taser_he.cfg`

Same as `knife.cfg`, but with taser and HE grenade.

Useful for knife rounds with a twist.

### `aim.cfg`

Config for aim maps with kevlar vest and helmet.

**Note:** Some aim maps don't support kevlar vest and helmet.

### `aim_kevlar.cfg`

Same as `aim.cfg`, but with kevlar vest only.

**Note:** Some aim maps don't support kevlar vest.

### `deathmatch.cfg`

Config for free-for-all (FFA) deathmatch with AK-47 as primary weapon, Deagle as secondary weapon, kevlar vest and helmet.

Useful as default warmup (spawning in the base) alternative.

### `deathmatch_hs.cfg`

Same as `deathmatch.cfg`, but with headshots only.

Useful as default warmup (spawning in the base) alternative.