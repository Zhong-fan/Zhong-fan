<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&amp;size=28&amp;duration=3200&amp;pause=900&amp;color=2F81F7&amp;center=true&amp;vCenter=true&amp;repeat=true&amp;width=760&amp;height=55&amp;lines=Hello%21%20Remember%20to%20eat%20lunch%21%20%F0%9F%91%8B%3BBaking%20bread%20%26%20making%20milk%20drinks%3BStill%20honing%20my%20sleep%20skills%20%F0%9F%98%B4" alt="Hello! Remember to eat lunch! 👋; Baking bread &amp; making milk drinks; Still honing my sleep skills 😴" />
</p>


<p align="center">
  <a href="https://x.com/Jidechizhongfan"><img src="https://img.shields.io/badge/X-%40Jidechizhongfan-000000?style=for-the-badge&amp;logo=x&amp;logoColor=white" alt="X: @Jidechizhongfan" /></a>
</p>

<p align="center">
  <a href="https://github.com/Zhong-fan"><img src="https://img.shields.io/github/followers/Zhong-fan?style=for-the-badge&amp;logo=github&amp;logoColor=white&amp;color=8B5CF6" alt="GitHub followers" /></a>
  <a href="https://github.com/Zhong-fan?tab=repositories"><img src="https://img.shields.io/github/stars/Zhong-fan?style=for-the-badge&amp;logo=githubsponsors&amp;logoColor=white&amp;color=EA580C" alt="GitHub stars" /></a>
  <img src="https://komarev.com/ghpvc/?username=Zhong-fan&amp;style=for-the-badge&amp;color=blueviolet" alt="Profile views" />
</p>

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&amp;logo=openjdk&amp;logoColor=white" alt="Java" height="32" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" height="32" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black" alt="JavaScript" height="32" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python" height="32" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&amp;logo=rust&amp;logoColor=white" alt="Rust" height="32" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&amp;logo=mysql&amp;logoColor=white" alt="MySQL" height="32" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&amp;logo=nodedotjs&amp;logoColor=white" alt="Node.js" height="32" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&amp;logo=vuedotjs&amp;logoColor=white" alt="Vue.js" height="32" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&amp;logo=springboot&amp;logoColor=white" alt="Spring Boot" height="32" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&amp;logo=dotnet&amp;logoColor=white" alt=".NET" height="32" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions" height="32" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&amp;logo=docker&amp;logoColor=white" alt="Docker" height="32" />
</p>

---

## Contributions

<p align="center">Selected merged work across seven public repositories</p>

### [REA](https://github.com/morluto/rea) <a href="https://github.com/morluto/rea/stargazers"><img alt="GitHub stars" src="https://badgen.net/github/stars/morluto/rea" height="20" /></a>

- **Implemented [.NET single-file bundle inspection and extraction](https://github.com/morluto/rea/pull/3787)**, so `inspect-artifact` and `extract-artifact` plus their MCP equivalents inventory and materialize PE, ELF and thin Mach-O apphosts across v1.0, v2.0 and v6.0 headers, including raw-DEFLATE members ([#2352](https://github.com/morluto/rea/issues/2352)).
- **Added [raw NMOS 6502 analysis support](https://github.com/morluto/rea/pull/2079)** to Ghidra for explicitly selected, headerless 6502 images, with load-address handling and checks against the original file bytes.
- **Fixed [file-offset resolution in Ghidra decompilation](https://github.com/morluto/rea/pull/2101)**, so decompiled functions map to the correct locations in the original file.
- **Contributed fixes to inline `Evidence` admission**, rejecting accessors and executable array members before parsing and bounding array admission. The work was integrated into [#3613](https://github.com/morluto/rea/pull/3613).
- **Implemented classic iNES region inspection and extraction** ([#2087](https://github.com/morluto/rea/pull/2087)), merged through [#2816](https://github.com/morluto/rea/pull/2816).

### [claude-mem](https://github.com/thedotmack/claude-mem) <a href="https://github.com/thedotmack/claude-mem/stargazers"><img alt="GitHub stars" src="https://badgen.net/github/stars/thedotmack/claude-mem" height="20" /></a>

- **Made failed [post-delete Chroma cleanups retryable](https://github.com/thedotmack/claude-mem/pull/5673)**, so documents left behind by an outage are recorded in the sync checkpoint and drained by the next backfill or the first reconnect ([#5664](https://github.com/thedotmack/claude-mem/issues/5664)).
- **Replaced the ["~10x token savings" claim](https://github.com/thedotmack/claude-mem/pull/5889)** with the measured per-result size ratio across the README, the architecture and usage pages, the mem-search skill and the MCP tool descriptions ([#4138](https://github.com/thedotmack/claude-mem/issues/4138)).
- **Made MCP [`save_memory` respect `CLAUDE_MEM_EXCLUDED_PROJECTS`](https://github.com/thedotmack/claude-mem/pull/6105)** by forwarding the caller's checkout, so an excluded project's note is refused instead of stored and the reply says why ([#6098](https://github.com/thedotmack/claude-mem/issues/6098)).
- **Coalesced [per-row Chroma sync-state writes](https://github.com/thedotmack/claude-mem/pull/6204)** into one checkpoint flush per 250 ms window, turning the O(n²) write pattern of a large backfill into a bounded one without changing crash recovery ([#6203](https://github.com/thedotmack/claude-mem/issues/6203)).
- **Made [hook-spool drains asynchronous and bounded](https://github.com/thedotmack/claude-mem/pull/6260)** with 256-entry parallel batches, so a backlog left by an outage no longer blocks the worker's event loop while health checks and hooks share it ([#6247](https://github.com/thedotmack/claude-mem/issues/6247)).
- **Surfaced [expired live-observer inputs in processing status](https://github.com/thedotmack/claude-mem/pull/6394)**, so an installation can tell how much queued work the observer dropped instead of only seeing a per-prune warning in the log ([#6391](https://github.com/thedotmack/claude-mem/issues/6391)).

### [Super Productivity](https://github.com/super-productivity/super-productivity) <a href="https://github.com/super-productivity/super-productivity/stargazers"><img alt="GitHub stars" src="https://badgen.net/github/stars/super-productivity/super-productivity" height="20" /></a>

- **Preserved priority across recurring tasks**, adding a series-level default that carries to future occurrences while retaining per-task overrides ([#10821](https://github.com/super-productivity/super-productivity/pull/10821)).
- **Fixed configured previous/next task navigation on project group headers**, so shortcuts can continue across grouped tasks ([#10822](https://github.com/super-productivity/super-productivity/pull/10822)).

### [Ludusavi](https://github.com/mtkennerly/ludusavi) <a href="https://github.com/mtkennerly/ludusavi/stargazers"><img alt="GitHub stars" src="https://badgen.net/github/stars/mtkennerly/ludusavi" height="20" /></a>

- **Made the duplicates filter easier to clear** by keeping the status-row badge available after matching games are hidden or conflicts are resolved, for both backup and restore ([#655](https://github.com/mtkennerly/ludusavi/pull/655)).

### [ooosplat](https://github.com/ooolabdev/ooosplat) <a href="https://github.com/ooolabdev/ooosplat/stargazers"><img alt="GitHub stars" src="https://badgen.net/github/stars/ooolabdev/ooosplat" height="20" /></a>

- **Improved FFprobe preflight diagnostics**, distinguishing engine startup failures from invalid video input, saving diagnostic logs before project creation, and showing detailed engine health information ([#54](https://github.com/ooolabdev/ooosplat/pull/54)).

### [OpenPI](https://github.com/openpi-dev/openpi) <a href="https://github.com/openpi-dev/openpi/stargazers"><img alt="GitHub stars" src="https://badgen.net/github/stars/openpi-dev/openpi" height="20" /></a>

- **Made the web UI's [Plan Ready handoff actionable](https://github.com/openpi-dev/openpi/pull/634)**, so a prepared plan can be continued from the interface.

### [Seiso](https://github.com/scarletkc/seiso) <a href="https://github.com/scarletkc/seiso/stargazers"><img alt="GitHub stars" src="https://badgen.net/github/stars/scarletkc/seiso" height="20" /></a>

- **Linked diagnostics to versioned rule documentation** in JSON and SARIF output, so editors and code review tools can open the explanation for a finding ([#22](https://github.com/scarletkc/seiso/pull/22)).
- **Cached duplicate-prefix sort keys** to avoid repeating the same work during rule evaluation ([#88](https://github.com/scarletkc/seiso/pull/88)).
- **Resolved GitHub annotation paths** from the repository root, so annotations point to the right source files ([#89](https://github.com/scarletkc/seiso/pull/89)).
- **Made inherited configuration lists additive**, allowing child configurations to extend parent lists ([#38](https://github.com/scarletkc/seiso/pull/38)).

[More merged contributions](https://github.com/pulls?q=is%3Apr+author%3AZhong-fan+is%3Amerged)


---

<details open>
<summary><b>🐍 Contribution Snake</b></summary>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Zhong-fan/Zhong-fan/output/github-contribution-grid-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/Zhong-fan/Zhong-fan/output/github-contribution-grid-snake.svg" alt="Contribution snake animation" width="100%" />
  </picture>
</p>

</details>
