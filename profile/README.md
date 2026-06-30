<div align="center">

# W4VE

### *Ware 4 Vanilla Experience*

Open mods, plugins and tooling for Minecraft's technical / vanilla-engineering crowd.

[![Website](https://img.shields.io/badge/web-w4ve.xyz-5865F2)](https://w4ve.xyz/)
[![Community](https://img.shields.io/badge/server-MineWave-brightgreen?logo=minecraft)](https://w4ve.xyz/)

</div>

---

**W4VE** (say it "Wave") is a small ecosystem of things we build for our own Minecraft
servers and then release for everyone. The philosophy is boring on purpose: **one jar you
install and it just works**, a bot you drop in, tooling that runs without a manual. No bloat,
no twenty dependencies to chase.

The name is a backronym: the **4** reads as *for* and **VE** is *Vanilla Experience* (a wink
at the vanilla-engineering community), so **Ware 4 Vanilla Experience** = software for getting
more out of vanilla Minecraft.

## Projects

| Project | What it is |
| --- | --- |
| **[WaveMotes](https://github.com/CodeW4VE/WaveMotes)** | Fabric **client** mod: type `:emote:` in chat and pick it from a `/`-style popup. Emotes render client-side (textures baked into the jar), plus optional Discord emojis. One jar, no deps. |
| **[ChatBridge](https://github.com/CodeW4VE/ChatBridge)** | Discord &harr; Minecraft chat bridge (fork of [TIS ChatBridge](https://github.com/TISUnion/ChatBridge)) that makes Minecraft players show up as themselves in Discord via webhooks. |

*More on the way.*

## Where it runs

This stuff powers **[MineWave](https://w4ve.xyz/)**, our Minecraft community: custom emotes
that everyone sees in-game and that bridge to and from Discord, cross-server chat, and the
rest of the plumbing. WaveMotes is the client half of that emote system; the server side does
the heavy lifting so even vanilla players see the emotes.
