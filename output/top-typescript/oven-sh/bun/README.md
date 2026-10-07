# oven-sh/bun

Generated: 2026-10-07T10:53:26.616234+00:00

- Unassigned: 59+
- [View all unassigned issues](https://github.com/oven-sh/bun/issues?q=is%3Aissue%20is%3Aopen%20no%3Aassignee)

Most recently opened:

| Issue | Comments |
|---|---|
| [#44689 bun check: NodeJS.BuiltinIteratorReturn evaluates to unknown when @types/bun is loaded (false TS2322 on URL; tsc 7 accepts)](https://github.com/oven-sh/bun/issues/44689) | 0 |
| [#44686 `bun check`: no TS2345 when a generic key indexes an intersection containing a mapped type](https://github.com/oven-sh/bun/issues/44686) | 0 |
| [#44684 node:module: an overridden Module.prototype._compile is never called for require()d CommonJS (and Module._load is never called)](https://github.com/oven-sh/bun/issues/44684) | 0 |
| [#44683 node:stream/iter: `fromWritable(req, { backpressure: "block" }).writev()` never resolves when the batch fills the cork buffer of a chunked request](https://github.com/oven-sh/bun/issues/44683) | 0 |
| [#44679 Bun shell mv: a cross-device move that fails midway leaves the tree split between source and destination](https://github.com/oven-sh/bun/issues/44679) | 0 |
| [#44677 node:http: OutgoingMessage fixes from node v26.5.0 to v26.10.0 that are not ported](https://github.com/oven-sh/bun/issues/44677) | 0 |
| [#44675 bun install: a streamed tarball fails when a body chunk ends inside a tar sparse map or a large pax header](https://github.com/oven-sh/bun/issues/44675) | 0 |
| [#44672 hoisted: the pass that removes nested copies after `bun update` runs before a failed run exits and reports nothing](https://github.com/oven-sh/bun/issues/44672) | 0 |
| [#44671 `bun prune` follows a root `node_modules` or `node_modules/.bun` that is a symlink](https://github.com/oven-sh/bun/issues/44671) | 0 |
| [#44670 hoisted: `bun prune` and `bun update` remove packages `bun.lock` places when a self-contained workspace depends on a sibling](https://github.com/oven-sh/bun/issues/44670) | 0 |
| [#44669 `bun prune` and `bun update` remove packages behind a workspace `node_modules` that is a symlink](https://github.com/oven-sh/bun/issues/44669) | 0 |
| [#44661 Repeated variable-sized Buffer.alloc(size, 1) is slower than Node in a single-VM bounded-retention loop](https://github.com/oven-sh/bun/issues/44661) | 2 |
| [#44660 bun check: "A is not assignable to A" for a contextually typed generic arrow that returns Promise#then inside a generic call (tsc 7 accepts)](https://github.com/oven-sh/bun/issues/44660) | 0 |
| [#44659 Extensionless import resolves to a file whose name differs only in case (fooBar.ts vs FooBar.tsx) on a case-sensitive file system](https://github.com/oven-sh/bun/issues/44659) | 1 |
| [#44658 CSS: oklch() in fill, stroke, caret-color and caret is never lowered](https://github.com/oven-sh/bun/issues/44658) | 0 |
| [#44657 bun check: unbounded memory growth (>13 GiB, OOM-killed) in nested overload resolution on a project tsc 7 checks in 8 s / 2 GiB](https://github.com/oven-sh/bun/issues/44657) | 0 |
| [#44656 bun check: TS2589 "excessively deep" on the first of two identical Kobalte polymorphic components (tsc 7 accepts)](https://github.com/oven-sh/bun/issues/44656) | 0 |
| [#44655 bun check: callback parameter inferred as `unknown` when the call result feeds a loop variable (tsc 7 accepts)](https://github.com/oven-sh/bun/issues/44655) | 0 |
| [#44653 node:http2: a received GOAWAY does not close the streams above its last-stream-id as node does](https://github.com/oven-sh/bun/issues/44653) | 0 |
| [#44650 AsyncLocalStorage store is not available inside process.on('unhandledRejection') listeners (Node restores it)](https://github.com/oven-sh/bun/issues/44650) | 0 |
| [#44644 `new Response(s3file)`: a static route and some copies answer a URL that S3 refuses](https://github.com/oven-sh/bun/issues/44644) | 0 |
| [#44643 bunfig.toml: add `test.isolate` and a test file `include` pattern](https://github.com/oven-sh/bun/issues/44643) | 0 |
| [#44642 bun test: per-file test environment (preload and isolate selected by glob), so DOM and server tests can share one run](https://github.com/oven-sh/bun/issues/44642) | 0 |
| [#44640 CSS: gamut mapping returns at the first chroma under the JND, so sRGB fallbacks come out desaturated](https://github.com/oven-sh/bun/issues/44640) | 1 |
| [#44639 CSS: oklch() inside filter and backdrop-filter drop-shadow() is never lowered](https://github.com/oven-sh/bun/issues/44639) | 0 |
| [#44635 install: three mimalloc heaps are created and destroyed for each package.json](https://github.com/oven-sh/bun/issues/44635) | 0 |
| [#44634 bun install zero-fills one path buffer of lockfile string space for each workspace (98 KB each on Windows)](https://github.com/oven-sh/bun/issues/44634) | 0 |
| [#44633 Windows: closing a ServerWebSocket inside open() drops the 101; clients see 1006 without open (Bun 1.4.2)](https://github.com/oven-sh/bun/issues/44633) | 0 |
| [#44631 Bun.YAML.parse: a merged key replaces an own key when the two are different YAML types with the same property name](https://github.com/oven-sh/bun/issues/44631) | 0 |
| [#44626 Windows: importing a module from a read-execute-only folder fails with EPERM (loader opens files with FILE_WRITE_ATTRIBUTES)](https://github.com/oven-sh/bun/issues/44626) | 2 |
| [#44608 Error.stack loses its message and function names when first materialized during GC](https://github.com/oven-sh/bun/issues/44608) | 0 |
| [#44607 bun test --changed crashes when a selected test terminates a busy Worker](https://github.com/oven-sh/bun/issues/44607) | 0 |
| [#44606 fs.realpathSync / fs.promises.realpath throw EPERM on macOS File Provider (CloudStorage) directories that lstat and stat can read](https://github.com/oven-sh/bun/issues/44606) | 1 |
| [#44605 bun:test: useFakeTimers ignores `toFake` (and `doNotFake`), so the faked set cannot be chosen](https://github.com/oven-sh/bun/issues/44605) | 1 |
| [#44604 node:dgram: socket.setMulticastTTL(0) throws EINVAL on Windows (Node accepts 0)](https://github.com/oven-sh/bun/issues/44604) | 0 |
| [#44603 Runtime Bun.plugin onResolve does not fire for bare package specifiers](https://github.com/oven-sh/bun/issues/44603) | 1 |
| [#44602 Bun.$ broken-pipe subprocess intermittently captures grep ECONNRESET stderr on Linux](https://github.com/oven-sh/bun/issues/44602) | 0 |
| [#44600 Nested object spread is ~38% slower than Node on Bun 1.4.2](https://github.com/oven-sh/bun/issues/44600) | 1 |
| [#44598 Performance drops due to Windows Defender scanning `.pile` cache files](https://github.com/oven-sh/bun/issues/44598) | 0 |
| [#44597 Bun.YAML.parse folds multiline quoted scalars differently for CRLF and LF](https://github.com/oven-sh/bun/issues/44597) | 0 |
| [#44595 FreeBSD: process hangs on exit after a successful conversation (JSC thread-suspend signal sent but never handled)](https://github.com/oven-sh/bun/issues/44595) | 1 |
| [#44594 RealAudio/RealVideo MIME types incorrect](https://github.com/oven-sh/bun/issues/44594) | 0 |
| [#44587 fs.rm with force fails with ENOTDIR on a missing path with a trailing slash (gVisor)](https://github.com/oven-sh/bun/issues/44587) | 3 |
| [#44586 bun test --parallel: worker SIGSEGV in JSFinalizationRegistry::takeDeadHoldingsValue (no native addons)](https://github.com/oven-sh/bun/issues/44586) | 0 |
| [#44585 fs.realpathSync.native resolves ".." before following a symlink, unlike node](https://github.com/oven-sh/bun/issues/44585) | 0 |
| [#44584 Lifecycle scripts have no equivalent for `run.bun`](https://github.com/oven-sh/bun/issues/44584) | 0 |
| [#44583 Object-property deletion/reinsertion is ~130x slower than Node (1.4.2 + canary)](https://github.com/oven-sh/bun/issues/44583) | 1 |
| [#44582 Bash completions don't suggest files](https://github.com/oven-sh/bun/issues/44582) | 0 |
| [#44578 Bun binds `this` for an unbound tagged-template call](https://github.com/oven-sh/bun/issues/44578) | 0 |
| [#44577 [FEATURE] TCP User Timeout for FetchSession and Sockets](https://github.com/oven-sh/bun/issues/44577) | 0 |
| [#44576 node:fs: recursive mkdir of "." or ".." throws EEXIST on Windows](https://github.com/oven-sh/bun/issues/44576) | 0 |
| [#44574 Worker drops messages posted during its top-level await (regression in 1.4.0)](https://github.com/oven-sh/bun/issues/44574) | 0 |
| [#44572 bun build --compile executable deadlocks on FreeBSD/aarch64 while bun run works](https://github.com/oven-sh/bun/issues/44572) | 3 |
| [#44570 Android/Termux: HTML dev server browser shortcut invokes /system/bin/am and fails with SecurityException](https://github.com/oven-sh/bun/issues/44570) | 0 |
| [#44568 Typo in src/clap/lib.rs doc comment: "paramter" should be "parameter"](https://github.com/oven-sh/bun/issues/44568) | 0 |
| [#44567 Subprocess.kill(signalName) sends Linux signal numbers on FreeBSD](https://github.com/oven-sh/bun/issues/44567) | 0 |
| [#44565 Android/Termux: CouldntReadCurrentDirectory on shared storage when an ancestor returns ENOENT (patch included)](https://github.com/oven-sh/bun/issues/44565) | 2 |
| [#44562 panic: index out of bounds (JSC) when a host compiles a large TS extension file — deterministic, sourcemap offset suspected](https://github.com/oven-sh/bun/issues/44562) | 1 |
| [#44561 macOS arm64: LLInt exception assertion during microtask drain in Bun 1.4.2 embedded in OpenCode](https://github.com/oven-sh/bun/issues/44561) | 0 |
