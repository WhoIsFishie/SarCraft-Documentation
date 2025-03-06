In the tumultuous history of SarCraft, certain players are remembered for their battles and conquests, while others leave their mark through the systems and infrastructure they build. **Udit** falls definitively into the latter category - a programmer whose well-intentioned authentication system would inadvertently become the source of SarCraft's most infamous exploits.

## The Authentication Pioneer

Udit joined the SarCraft community not primarily as a player but as a technical contributor. His most significant contribution came during the pre-launch testing phase of [[Season 5]], where he created an experimental Telegram-based authentication system designed to enhance server security.

The "Minegram" system, as it was known, represented a novel approach to Minecraft server authentication. Rather than relying on standard password-based systems, Udit's creation connected the Minecraft server directly to Telegram, allowing players to authenticate using the messaging platform.

## Minegram: The Double-Edged Sword

What began as a security enhancement would soon evolve into an unintentional weapon that shaped multiple seasons of SarCraft history. The Minegram system featured three critical vulnerabilities that would be weaponized by players.

## The Technical Deep Dive

For those technically inclined, Udit's system struggled with its core architectural approach. The Minegram authentication was essentially a wrapper around the Minecraft server that parsed log output to handle authentication. This created race conditions when multiple players interacted with the system simultaneously - the fundamental issue behind most of the exploits.

A core part of the problem lay in how the plugin monitored server logs:

```
// Parser module
// Parses Minecraft server cli
// log and acts as necessary
func Parser(data utils.ModuleData) {
    scanner := bufio.NewScanner(*data.Stdout)
    go func() {
        defer (*data.Waitgroup).Done()
        for scanner.Scan() {
            m := scanner.Text()
            logFeed <- m
            // ... further processing
        }
    }()
}
```


This log-parsing approach created numerous edge cases that couldn't be properly handled, leading to the infamous teleportation bugs and identity confusion that would plague multiple SarCraft seasons.