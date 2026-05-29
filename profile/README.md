<h1 align="center">SPACE0</h1>

<p align="center"><em>Creating worlds through word.</em></p>

<p align="center">
  AI-native Minecraft that runs in your browser.<br>
  Build a world, share the link, friends walk in. No download.
</p>

<p align="center">
  <a href="https://0.space"><img alt="Enter 0.space" src="https://img.shields.io/badge/0.space-enter-38C776?style=for-the-badge&labelColor=0d0d0d"></a>
  <a href="https://blog.0.space"><img alt="Read the blog" src="https://img.shields.io/badge/blog-the_next_internet_is_3D-0d0d0d?style=for-the-badge"></a>
</p>

<p align="center">
  <img alt="Web" src="https://img.shields.io/badge/web-0d0d0d?style=flat-square">
  <img alt="iOS" src="https://img.shields.io/badge/iOS-0d0d0d?style=flat-square">
  <img alt="macOS" src="https://img.shields.io/badge/macOS-0d0d0d?style=flat-square">
  <img alt="Windows" src="https://img.shields.io/badge/Windows-0d0d0d?style=flat-square">
  <img alt="Rust" src="https://img.shields.io/badge/engine-Rust-0d0d0d?style=flat-square">
</p>

---

### The next Internet is 3D

The internet grows one medium at a time. Text connected information. Images opened visual expression. Video added time and sound. The next medium is space.

The metaverse tried to move you into a separate virtual world behind a headset. We go the other way: same browser, same links, same search. Only the medium changes. A web page becomes a web space.

### How it works

| Make | Share | Gather |
|------|-------|--------|
| Place blocks, shape terrain, craft objects. Smooth surfaces, not just cubes. | Every world is a URL. Send the link. | Friends drop in and build with you, in real time. |

Name a space and start building in about 30 seconds. No install, no launcher, no server to set up. A link is the whole invitation.

### Under the hood

- **Browser-native 3D.** WebGPU and WASM. Nothing to download.
- **One Rust engine, every device.** A clean-slate Rust voxel and terrain engine drives web, iOS, macOS, and Windows.
- **A world from a seed.** A physics-first engine derives a whole planet, its geology, climate, water, and life, from a 128-bit seed across 16 planet classes. Same seed, same world.
- **Byte-identical worlds.** The engine is bit-for-bit deterministic across platforms, checked in CI on every change, so every device sees the same world.
- **Voxels with curves.** Dual Contouring keeps building intuitive (stack and break) while rendering smooth surfaces and sharp edges, not only cubes.
- **A world that reacts.** A small set of material properties (temperature, mass, hardness, fluidity, reactivity) produces emergent physics. Heat melts stone, fire spreads and structures collapse, water freezes. You discover the rules; we did not script them one by one.

### What we're exploring

A few threads we're pulling on, quietly.

- **3D memory for agents.** AI teammates that remember a space the way you remember a room, by where things are, not by scrolling a transcript. We think a voxel world is the right substrate for it, and we're writing up why.
- **One renderer, from scratch.** Moving the client onto a single Rust and WebGPU renderer, so what you build looks the same everywhere it runs.
- **Worlds you can describe.** Tell it what you want, or show it a picture, and it comes back as real, editable voxels, not a flat image.

No roadmap, no hype. We ship it when it is bit-for-bit correct.

### Open source

> [!TIP]
> **[slintcn](https://github.com/zero-sq/slintcn)** &nbsp;·&nbsp; shadcn/ui-style copy-paste components for [Slint](https://slint.dev) native apps.
> 56 components, 8 installable blocks, a theme system, and a self-hostable registry. The components behind our desktop client, free for anyone building Slint apps.
>
> <a href="https://github.com/zero-sq/slintcn"><img alt="slintcn stars" src="https://img.shields.io/github/stars/zero-sq/slintcn?style=social"></a>

### Find us

- **Try it** &nbsp;·&nbsp; [0.space](https://0.space)
- **Read the thesis** &nbsp;·&nbsp; [blog.0.space](https://blog.0.space)
- **Follow** &nbsp;·&nbsp; [@space_zero_](https://x.com/space_zero_) on X

<p align="center"><sub>A product of Space Zero, Inc.</sub></p>
