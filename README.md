你好！记得吃中饭！

## Contributions

### [REA](https://github.com/morluto/rea) [![GitHub stars](https://img.shields.io/github/stars/morluto/rea?style=flat&label=stars)](https://github.com/morluto/rea/stargazers)

- Added [raw NMOS 6502 analysis support](https://github.com/morluto/rea/pull/2079) to Ghidra for explicitly selected, headerless 6502 images, with load-address handling and checks against the original file bytes.
- Fixed [file-offset resolution in Ghidra decompilation](https://github.com/morluto/rea/pull/2101), so decompiled functions map to the correct locations in the original file.
- Added [classic iNES region inspection and extraction](https://github.com/morluto/rea/pull/2816), with checks that tie extracted regions back to the inspected input. This work is ongoing in #2816; the initial PR, [#2087](https://github.com/morluto/rea/pull/2087), was closed in favor of this continuation.

### [Seiso](https://github.com/scarletkc/seiso) [![GitHub stars](https://img.shields.io/github/stars/scarletkc/seiso?style=flat&label=stars)](https://github.com/scarletkc/seiso/stargazers)

- Linked diagnostics to versioned rule documentation in JSON and SARIF output, so editors and code review tools can open the explanation for a finding ([#22](https://github.com/scarletkc/seiso/pull/22)).
- Cached duplicate-prefix sort keys to avoid repeating the same work during rule evaluation ([#88](https://github.com/scarletkc/seiso/pull/88)).
- Resolved GitHub annotation paths from the repository root, so annotations point to the right source files ([#89](https://github.com/scarletkc/seiso/pull/89)).
- Made inherited configuration lists additive, allowing child configurations to extend parent lists ([#38](https://github.com/scarletkc/seiso/pull/38)).

### [OpenPI](https://github.com/openpi-dev/openpi) [![GitHub stars](https://img.shields.io/github/stars/openpi-dev/openpi?style=flat&label=stars)](https://github.com/openpi-dev/openpi/stargazers)

- Made the web UI's [Plan Ready handoff actionable](https://github.com/openpi-dev/openpi/pull/634), so a prepared plan can be continued from the interface.

[More merged contributions](https://github.com/pulls?q=is%3Apr+author%3AZhong-fan+is%3Amerged)
