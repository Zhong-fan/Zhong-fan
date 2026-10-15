Hello! Remember to eat lunch!

I'm an eating engineer from Hangzhou, Zhejiang, China. I specialize in bread baking and making milk-based drinks, and I've spent years honing my sleep skills.

[X: @Jidechizhongfan](https://x.com/Jidechizhongfan)

## Contributions

### [REA](https://github.com/morluto/rea) [![GitHub stars](https://img.shields.io/github/stars/morluto/rea?style=flat&label=stars)](https://github.com/morluto/rea/stargazers)

- Added [raw NMOS 6502 analysis support](https://github.com/morluto/rea/pull/2079) to Ghidra for explicitly selected, headerless 6502 images, with load-address handling and checks against the original file bytes. The contribution was credited by name in the [REA 6.5.0 release notes](https://github.com/morluto/rea/releases/tag/rea-agents-6.5.0).
- Fixed [file-offset resolution in Ghidra decompilation](https://github.com/morluto/rea/pull/2101), so decompiled functions map to the correct locations in the original file. Both Ghidra contributions are included in the [REA 6.5.0 release notes](https://github.com/morluto/rea/releases/tag/rea-agents-6.5.0), which credit @Zhong-fan by name.
- Contributed fixes to inline `Evidence` admission, rejecting accessors and executable array members before parsing and bounding array admission. The work was integrated into [#3613](https://github.com/morluto/rea/pull/3613), a merged PR opened by N0zoM1z0 that preserves the original Git history and records GitHub co-author credit.
- Implemented classic iNES region inspection and extraction, with follow-up work in [#2816](https://github.com/morluto/rea/pull/2816).

### [Seiso](https://github.com/scarletkc/seiso) [![GitHub stars](https://img.shields.io/github/stars/scarletkc/seiso?style=flat&label=stars)](https://github.com/scarletkc/seiso/stargazers)

- Linked diagnostics to versioned rule documentation in JSON and SARIF output, so editors and code review tools can open the explanation for a finding ([#22](https://github.com/scarletkc/seiso/pull/22)).
- Cached duplicate-prefix sort keys to avoid repeating the same work during rule evaluation ([#88](https://github.com/scarletkc/seiso/pull/88)).
- Resolved GitHub annotation paths from the repository root, so annotations point to the right source files ([#89](https://github.com/scarletkc/seiso/pull/89)).
- Made inherited configuration lists additive, allowing child configurations to extend parent lists ([#38](https://github.com/scarletkc/seiso/pull/38)).

### [OpenPI](https://github.com/openpi-dev/openpi) [![GitHub stars](https://img.shields.io/github/stars/openpi-dev/openpi?style=flat&label=stars)](https://github.com/openpi-dev/openpi/stargazers)

- Made the web UI's [Plan Ready handoff actionable](https://github.com/openpi-dev/openpi/pull/634), so a prepared plan can be continued from the interface.

[More merged contributions](https://github.com/pulls?q=is%3Apr+author%3AZhong-fan+is%3Amerged)
