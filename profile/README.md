<div align="center">

# Bowbox

**We make things for Valve games, and take them apart to see how they work.**

</div>

<br>

<table>
<tr>
<td width="50%" align="center" valign="top">
<img src="https://raw.githubusercontent.com/Bowbox/.github/main/profile/srcds.png" width="72" height="72" alt="srcds"><br>
<b>Before</b> · srcds<br><br>
<video src="https://github.com/user-attachments/assets/612e5aae-1abd-48d6-abc5-71c88d4a6c1a" controls muted loop width="100%"></video>
</td>
<td width="50%" align="center" valign="top">
<img src="https://avatars.githubusercontent.com/u/200423184?s=200&v=4" width="72" height="72" alt="Bowbox"><br>
<b>After</b> · Bowbox<br><br>
<video src="https://github.com/user-attachments/assets/cf4cf6b1-ec46-4def-91f6-69d444d2c155" controls muted loop width="100%"></video>
</td>
</tr>
</table>

<br>

## Who we are

A small team of developers who keep coming back to Valve games and the Source engine. Most of us got here through Half-Life mods and Garry's Mod, and we never really left. We like the engine's quirks and its networking, and the odd decisions someone made twenty years ago that still shape how these games behave.

We build projects, and we run experiments. Some experiments grow into projects. Others answer their question and stop there, which is fine too.

## Projects

<table>
<tr>
<td width="50%" valign="top">

### Server

A Garry's Mod server emulator written from scratch in Rust.

Real, unmodified GMod clients find it in the server browser, join `gm_construct` and play: walk around, spawn props, throw them with the physgun, drive the Jeep, climb ladders and swim.

It is multi-threaded, with physics on its own thread so the network never waits on it. The physics is the part we're proudest of, and the server stays fast and light on memory.

**Coming soon:** server-side anti-cheat against wallhacks.

`Rust` · `Source protocol 24`

*Not open source yet. We'll open it up when it's ready.*

</td>
<td width="50%" valign="top">

### Experiments

Smaller tools and prototypes around Source: its file formats, its networking, and whatever else we get curious about.

They land here once they're worth sharing, usually with notes on what we found out.

`Coming up`

</td>
</tr>
</table>

## How we work

- **Evidence over memory.** The Source SDK is a good start, but Garry's Mod differs from it in plenty of places. We check against real captures, demos and the game's own binaries before we trust a detail.
- **Write down what we learn.** If something took a day to figure out, the next person shouldn't need a day.
- **Small and working beats big and planned.**

## Say hello

Found a Source oddity you want to dig into, or have an idea for something we should try? Open an issue or start a discussion on any of our public repositories.

<br>

<sub>Bowbox is not affiliated with Valve or Facepunch Studios.</sub>
