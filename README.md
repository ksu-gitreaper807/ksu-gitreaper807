# Kushal Gowda S

Software engineer working across systems, machine learning, developer tools, and open-source multimedia.

## Current project tracker

_Last updated: 27 November 2026_

| Project | What I am building | Current state | Next checkpoint |
|---|---|---|---|
| [WAS'NRT](https://github.com/ksu-gitreaper807/gpuwasm) | A research runtime for trusted WebAssembly GPU workloads using Wasmtime and a direct Vulkan backend | **Active** — Vulkan ordering and teardown fixes, regression tests, and barrier measurements are on [PR #7](https://github.com/ksu-gitreaper807/gpuwasm/pull/7) | Preserve the queue-submission investigation and run a matched current-runtime vs native WebGPU benchmark on the same GPU |
| [3rd Sem EL](https://github.com/ksu-gitreaper807/EmbedEd) | A code-clone retrieval study comparing random, BM25, and semantic negative sampling | **Training** — Java250 Random seed 13 reached 92%; evaluation and backup follow, with BM25 and Semantic queued | Record F1 and checkpoint artifacts, then complete the queued retrieval conditions |
| [Tide Terminal](https://github.com/ksu-gitreaper807/tide-terminal) | A Linux terminal emulator with tabs, shell integration, command timers, output rules, shared history, and input alerts | **Usable** — version 0.1.0-11 is installed; the latest addition is a whole-window close shortcut with running-process confirmation | Clear two local test artifacts, run release checks, and tag the next stable build |
| [HALO: DSSB](https://github.com/k-karthik-pai/halo-discord) | A private Discord Activity and laptop-host integration for Halo | **Setup** — host integration is implemented; local Emscripten, server configuration, and assets are being connected | Finish the host build and configuration, then complete a local end-to-end connection test |
| [FFmpeg contributions](https://code.ffmpeg.org/FFmpeg/FFmpeg/pulls/25859) | `libswscale` optimizations and portable color-conversion experiments | **Merged + follow-up research** — [PR #25859](https://code.ffmpeg.org/FFmpeg/FFmpeg/pulls/25859) skips unused chroma conversion for grayscale output; a separate [Bayer validation harness](https://github.com/ksu-gitreaper807/ffmpeg-bayer-cfarm-validation) is ready | Validate the experimental Bayer-to-gray paths across AVX-512, ARM64, POWER, RISC-V, LoongArch, and s390x hardware |

## Links

- [Portfolio repository](https://github.com/ksu-gitreaper807/Portfolio)
- [LinkedIn](https://www.linkedin.com/in/kushal-gowda-a86508376/)
- [LeetCode](https://leetcode.com/u/SuedForAdultery/)

The tracker reports work in progress. Performance and research claims remain provisional until their linked validation steps are complete.
