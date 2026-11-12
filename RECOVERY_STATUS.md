# Vantoryn Desk — Reverse Recovery (analysis only)

This is a **separate recovery branch**. The released v6 binary on `main` is the reference; do not replace it with a simplified web interface.

## Verified static analysis (2026-11-12)

- Source: original v6 `VantorynDesk.exe` (SHA-256 `1cf014959f7787ae8f542b250ab36d8b8508dc65eb6751f5e339e085196b54f8`).
- Go 1.23.2; module `lumifloat`; Windows amd64.
- Go pclntab parsed successfully: **7,579 function records**, including **942** app-scoped functions (`main.` and `lumifloat/`).
- Function names, addresses, source paths and some line numbers recovered; these are **not original Go source code**.
- First analysis targets: `main.(*DesktopApp).createWidget`, `paintWidget`, `paintStocks`, `refreshStocks`, `main.(*gpuPerformanceSampler).read`, `main.captureResizeSnapshot`, `main.parsePresentMonCSV`, and related functions.
- Limited x86-64 disassembly has been produced locally for 11 functions, but not yet decompiled or converted into an original application build.

## Non-negotiable release criteria

1. Preserve Windows native interface, movable/independent widgets, layout and feature behavior; compare to original v6 screenshots and binary.
2. Do not present partial feature substitutions as a release or claim the original Go source has been recovered.
3. Every future release requires complete compilable source, build instructions, repeatable tests, and the corresponding Windows binary.
4. Keep `main` untouched until recovered native app has been tested and approved.

The full analysis bundle was delivered in the conversation: `VantorynDesk-v6-REAL-Reverse-Analysis-01.zip`.
