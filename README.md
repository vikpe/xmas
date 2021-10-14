# Instructions

## Locs
1) Backup existing loc files (`dm2.loc`, `dm3.loc`, `e1m2.loc`)
2) Download loc files to `/quake/qw/locs`

<br>

## Teamplay config
1) Download [`tvs_alias.cfg`](https://raw.githubusercontent.com/vikpe/xmas/main/tvs_alias.cfg) and [`tvs_tp.cfg`](https://raw.githubusercontent.com/vikpe/xmas/main/tvs_tp.cfg) to `/quake/id1`
2) Edit `tvs_tp.cfg`
3) Add `exec tvs_tp.cfg` at the bottom of you current config.

<br>

## Minimal European server list
1. Download [`europe_slim.txt`](https://raw.githubusercontent.com/vikpe/xmas/main/europe_slim.txt) to `/quake/ezquake/sb/`
2. Add `file "Europe slim" europe_slim.txt` to `/quake/ezquake/sb/sources.txt`
3. Add to your config: 
  ```
  sb_sourceunmarkall
  sb_sourcemark "Europe slim"
  ``` 
