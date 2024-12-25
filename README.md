# Better "bind <key> getpos | bind <key>" 
Fixing valves spaghetti code.

getpos teleports you into the air when you want to do a setpos later

getpos_exact returns a setpos that teleports you onto the floor, but the viewing angles are broken

These cfg's fix the ```bind <key> getpos | bind <key>``` binds (teleport you onto the floor with the right viewing angle)

### Usage

```bind <key> "exec better_getpos | grep %```

```bind <key> "exec better_setpos | grep %```
