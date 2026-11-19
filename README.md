<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Daniel&fontSize=64&fontColor=ffffff&fontAlignY=36&desc=Software%20Engineer&descAlignY=58&descSize=18&animation=fadeIn" alt="header" />
</p>

<p align="center">
  <a href="https://github.com/DaniuPl">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=58A6FF&center=true&vCenter=true&width=640&lines=Founder+of+ThreadGames;Unity+%26+C%23+developer+%E2%80%94+5%2B+years+commercial;Souls+of+Arcania+%E2%80%94+sci-fi+survival+on+my+own+engine;Writing+ThreadEngine%2C+my+own+C%2B%2B+game+engine;Building+ThreadOS%2C+an+OS+from+scratch+in+C;Games+first.+Low-level+always." alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://threadgames.pl"><img src="https://img.shields.io/badge/Studio-ThreadGames-c0392b?style=for-the-badge&logo=googlechrome&logoColor=white" alt="ThreadGames" /></a>
  <a href="https://github.com/DaniuPl"><img src="https://img.shields.io/github/followers/DaniuPl?label=Followers&style=for-the-badge&logo=github&color=24292e" alt="followers" /></a>
  <a href="https://github.com/DaniuPl/ThreadOS"><img src="https://img.shields.io/github/stars/DaniuPl/ThreadOS?label=ThreadOS%20stars&style=for-the-badge&logo=github&color=2c5364" alt="ThreadOS stars" /></a>
  <a href="https://discord.gg/AyaEyTSG6"><img src="https://img.shields.io/badge/Discord-ThreadOS-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <img src="https://komarev.com/ghpvc/?username=DaniuPl&style=for-the-badge&color=0e75b6&label=Profile+views" alt="profile views" />
</p>

---

## 👨‍💻 About me

```cpp
class Daniel final : public SoftwareEngineer
{
public:
    static constexpr std::string_view studio  = "ThreadGames";
    static constexpr std::string_view primary = "Unity / C#  (5+ years, commercial)";

    static constexpr std::array<std::string_view, 3> focus   { "Game development", "Game engines", "Operating systems" };
    static constexpr std::array<std::string_view, 5> writes  { "C++", "C", "Assembly", "Python", "JavaScript" };
    static constexpr std::array<std::string_view, 3> current { "Souls of Arcania", "ThreadEngine", "ThreadOS" };

    static constexpr std::string_view motto = "If it can be built from scratch, it can be understood.";
};
```

- 🎮 **Game development** — 5+ years of commercial work in **Unity / C#**: gameplay systems, tools and polished experiences.
- 🏢 **[ThreadGames](https://threadgames.pl)** — my indie studio.
- ⚔️ **Souls of Arcania** — our debut game: a harsh, atmospheric **sci-fi survival** set on an alien planet.
- ⚙️ **Engine programming** — I'm writing **ThreadEngine**, the studio's own 3D game engine in modern C++ that powers Souls of Arcania.
- 🖥️ **Systems** — I'm the author of **ThreadOS**, an operating system with its own kernel, drivers, filesystem, network stack and desktop.
- 🤝 Open to talking about code, games and collaborations — reach out on Discord.

---

## 🚀 Featured projects

### ⚔️ Souls of Arcania — sci-fi survival · *in development*
> A harsh, atmospheric **sci-fi survival** game set on an alien planet — made by **[ThreadGames](https://threadgames.pl)** on our own engine, **ThreadEngine**.

<table>
<tr>
<td width="33%" valign="top">

**🧭 Exploration**<br/>
A rough, unpredictable alien world to explore.

</td>
<td width="33%" valign="top">

**🔧 Survival & crafting**<br/>
Manage resources, build shelters, craft equipment.

</td>
<td width="33%" valign="top">

**⚔️ Demanding combat**<br/>
Face the threats of an alien biosphere in an unforgiving combat system.

</td>
</tr>
</table>

<p align="center">
  <a href="https://threadgames.pl"><img src="https://img.shields.io/badge/threadgames.pl-Souls%20of%20Arcania-c0392b?style=flat-square&logo=googlechrome&logoColor=white" alt="threadgames.pl" /></a>
  <img src="https://img.shields.io/badge/engine-ThreadEngine-2c5364?style=flat-square" alt="ThreadEngine" />
  <img src="https://img.shields.io/badge/genre-sci--fi%20survival-444444?style=flat-square" alt="sci-fi survival" />
  <img src="https://img.shields.io/badge/status-in%20development-f39c12?style=flat-square" alt="in development" />
</p>

### ⚙️ ThreadEngine — our own game engine
> The **ThreadGames** 3D engine and editor, written from scratch in **C++20** to power Souls of Arcania. *(private repository)*

<table>
<tr>
<td width="50%" valign="top">

**🎨 Rendering**
- DirectX 12 and OpenGL backends, PBR materials, IBL (SH9)
- HDR, bloom, SSAO, SSR, volumetric fog & god rays
- Node-based **Shader Graph** generating HLSL + GLSL, material instances, shader hot-reload
- Mesh LODs (meshoptimizer), instancing, GPU skinning

**🌍 World & gameplay**
- ECS on EnTT, **Jolt Physics**, OpenAL 3D audio
- World streaming in a cell grid, mesh terrain
- Navmesh AI (Recast/Detour) and **Behaviour Trees**
- Networking over ENet

</td>
<td width="50%" valign="top">

**🧰 Editor & tools**
- ImGui editor with gizmos, undo/redo, asset pickers
- Node editors for materials and behaviour trees
- CPU + GPU profiler, built-in Git window
- MCP server — an AI assistant can see the viewport and edit the scene
- Hub, CLI and game packaging

**📦 Platforms**
- Windows, Linux and **Android** (arm64) game builds

</td>
</tr>
</table>

<p align="center">
  <img src="https://img.shields.io/badge/C%2B%2B20-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++20" />
  <img src="https://img.shields.io/badge/DirectX%2012-107C10?style=flat-square&logo=xbox&logoColor=white" alt="DirectX 12" />
  <img src="https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white" alt="OpenGL" />
  <img src="https://img.shields.io/badge/HLSL%20%2F%20GLSL-444444?style=flat-square" alt="HLSL / GLSL" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/Dear%20ImGui-1E1E1E?style=flat-square" alt="Dear ImGui" />
  <img src="https://img.shields.io/badge/Jolt%20Physics-8A2BE2?style=flat-square" alt="Jolt Physics" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
</p>

### 🖥️ [ThreadOS](https://github.com/DaniuPl/ThreadOS) — an operating system from scratch

<p align="center">
  <a href="https://github.com/DaniuPl/ThreadOS">
    <img src="https://raw.githubusercontent.com/DaniuPl/ThreadOS/main/docs/desktop.png" width="88%" alt="ThreadOS desktop" />
  </a>
</p>

> An operating system for x86-64 PCs, written from scratch in **C and assembly** — and an ARM64 kernel that runs as a phone.

<table>
<tr>
<td width="50%" valign="top">

**🧠 Kernel**
- 64-bit long mode, 4-level paging with NX, SMP
- Processes & threads on all cores, `fork`/`exec`, copy-on-write, swap
- Signals, pipes, shared memory, shared libraries
- musl libc port with POSIX threads and sockets

**💾 Storage & boot**
- **TFS3** — own filesystem, plus FAT12/16/32
- **threadboot** — own UEFI loader, installer, signed updates
- AHCI, NVMe, ATA, USB (xHCI/EHCI/UHCI)

</td>
<td width="50%" valign="top">

**🌐 Network & security**
- ARP, IPv4, TCP, UDP, DHCP, DNS
- **TLS 1.3** with X.509 validation
- AES-GCM, ChaCha20-Poly1305, X25519, ECDSA, RSA

**🪟 Desktop**
- Compositor with themes, animations, virtual desktops
- File manager, terminal, editor, media player, settings
- **Weft** — web browser on a WPE WebKit port

**📱 ThreadOS mobile** — ARM64 kernel with touch, sound and apps

</td>
</tr>
</table>

<p align="center">
  <img src="https://raw.githubusercontent.com/DaniuPl/ThreadOS/main/docs/sharp.png" width="44%" alt="Calendar, calculator and menu" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/DaniuPl/ThreadOS/main/docs/devices.png" width="44%" alt="Device Manager" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/Assembly-6E4C13?style=flat-square&logo=assemblyscript&logoColor=white" alt="Assembly" />
  <img src="https://img.shields.io/badge/x86--64-0071C5?style=flat-square&logo=intel&logoColor=white" alt="x86-64" />
  <img src="https://img.shields.io/badge/ARM64-0091BD?style=flat-square&logo=arm&logoColor=white" alt="ARM64" />
  <img src="https://img.shields.io/badge/UEFI-555555?style=flat-square" alt="UEFI" />
  <img src="https://img.shields.io/badge/QEMU-FF6600?style=flat-square&logo=qemu&logoColor=white" alt="QEMU" />
  <img src="https://img.shields.io/badge/tests-100%2B%20QEMU%20groups-2ea44f?style=flat-square" alt="tests" />
  <img src="https://img.shields.io/github/license/DaniuPl/ThreadOS?style=flat-square" alt="license" />
</p>

---

## 🛠️ Tech stack

<p align="center">
  <b>Game dev</b><br/>
  <img src="https://skillicons.dev/icons?i=unity,cs,dotnet,cpp,blender&theme=dark" alt="game dev" />
</p>

<p align="center">
  <b>Languages</b><br/>
  <img src="https://skillicons.dev/icons?i=cpp,c,cs,py,js&theme=dark" alt="languages" />
</p>

<p align="center">
  <b>Data & tools</b><br/>
  <img src="https://skillicons.dev/icons?i=mysql,linux,bash,cmake,git,github,githubactions,visualstudio,idea,vscode&theme=dark" alt="tools" />
</p>

---

## 📊 GitHub stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=DaniuPl&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=tokyonight&bg_color=0d1117" alt="stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DaniuPl&layout=compact&langs_count=8&hide_border=true&theme=tokyonight&bg_color=0d1117" alt="top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=DaniuPl&hide_border=true&theme=tokyonight&background=0d1117" alt="streak" />
</p>

<p align="center">
  <img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=DaniuPl&hide_border=true&theme=tokyo-night&bg_color=0d1117" alt="activity graph" />
</p>

---

## 📫 Let's connect

<p align="center">
  <a href="https://threadgames.pl"><img src="https://img.shields.io/badge/Website-threadgames.pl-c0392b?style=for-the-badge&logo=googlechrome&logoColor=white" alt="threadgames.pl" /></a>
  <a href="mailto:kontakt@threadgames.pl"><img src="https://img.shields.io/badge/Email-kontakt%40threadgames.pl-0e75b6?style=for-the-badge&logo=gmail&logoColor=white" alt="email" /></a>
  <a href="https://github.com/DaniuPl"><img src="https://img.shields.io/badge/GitHub-DaniuPl-24292e?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://discord.gg/AyaEyTSG6"><img src="https://img.shields.io/badge/Discord-Join%20ThreadOS-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/DaniuPl/ThreadOS/releases/latest"><img src="https://img.shields.io/github/v/release/DaniuPl/ThreadOS?style=for-the-badge&label=ThreadOS%20release&color=2c5364" alt="release" /></a>
</p>

<!-- Footer -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" alt="footer" />
</p>
