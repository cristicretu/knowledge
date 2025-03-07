---
title: Zig
---

# [Zig](https://ziglang.org/)

[Ziglings](https://github.com/ratfactor/ziglings) is nice for learning.

## Notes

- [Zig compiler pipeline is: tokenize -> parse -> astgen -> sema -> codegen](https://twitter.com/andy_kelley/status/1388268643075563520)
- [Automatic error unions, required error handling, errdefer, and the try keyword really give Zig my favorite error handling feel of any language.](https://lobste.rs/s/xbncik/rust_first_thoughts)
- [Types are values in zig, this means that to create generic functions you pass the type as an argument and change the function logic based on that. This is also possible thanks to another feature, running code at compile time with comptime.](https://twitter.com/MichalZiulek/status/1502983958233034753)
- [Zig has good "surface area minimalism". comptime is just one keyword, but it replaces the entire C preprocessor (well, mostly), a template/generics system, type reflection, and probably a few more things. Same with the build system: I don't need to learn a separate language to describe builds, instead the build system is (mostly) just a stdlib module. It's true that the Zig's error handling, tagged unions, slices, etc... are "less minimalistic" than C, but those things exist to fix obvious problems of C in a way that would be hard to do in libraries, and because of this they are justified.](https://twitter.com/FlohOfWoe/status/1529095547273060353)

## Links

- [Zig Learn](https://ziglearn.org/) ([Code](https://github.com/Sobeston/ziglearn))
- [The Road to Zig 1.0 - Andrew Kelley (2019)](https://www.youtube.com/watch?v=Gv2I7qTux7g)
- [Pluto](https://github.com/SamTebbs33/pluto) - Hobby x86 kernel written in Zig.
- [Hobby x86 kernel written with Zig](https://github.com/jzck/kernel-zig) ([HN](https://news.ycombinator.com/item?id=21967668))
- [Zig Compiler Internals (2020)](https://www.youtube.com/watch?v=8MbREuiLQrM)
- [bootstrap-zig](https://github.com/ziglang/zig-bootstrap) - Start with minimum system dependencies and end with a fully operational Zig compiler for any target.
- [Zig 0.6.0 Release Notes](https://ziglang.org/download/0.6.0/release-notes.html) ([HN](https://news.ycombinator.com/item?id=22860008))
- [PBUI Project](https://pbui.codes/) - Standard library toolsets in the Zig programming language. ([Code](https://github.com/pbui-project/pbui-main))
- [A Brief Exploration of Zig (2020)](https://gsquire.github.io/static/post/a-brief-exploration-of-zig/)
- [zls](https://github.com/zigtools/zls) - Zig LSP implementation + Zig Language Server.
- [zls: A Zig Language Server - Alex Naskos & Auguste Rame (2020)](https://www.youtube.com/watch?v=r5fo7k-XIRI)
- [Why Zig When There is Already CPP, D, and Rust?](https://github.com/ziglang/zig/wiki/Why-Zig-When-There-is-Already-CPP,-D,-and-Rust%3F) ([Lobsters](https://lobste.rs/s/0h17xy/why_zig_when_there_is_already_cpp_d_rust))
- [Zig: a great fit for emulators - Benjamin Feng (2020)](https://www.youtube.com/watch?v=jkkUS0nmdsg) ([Lobsters](https://lobste.rs/s/gaoldu/zig_great_fit_for_emulators))
- [What is Zig's “Colorblind” Async/Await? (2020)](https://kristoff.it/blog/zig-colorblind-async-await/) ([Lobsters](https://lobste.rs/s/y3fsrm/what_is_zig_s_colorblind_async_await))
- [Zig Showtime](https://zig.show/) - Show where members of the Zig community share code and ideas.
- [Announcing the Zig Software Foundation (2020)](https://ziglang.org/news/announcing-zig-software-foundation.html) ([HN](https://news.ycombinator.com/item?id=23806222))
- [Zig Live Coding: Self-Hosted Incremental Compilation Debug Info + LLVM 11 Upgrade (2020)](https://www.youtube.com/watch?v=3CtQAaWUZrY)
- [Awesome Zig](https://github.com/catdevnull/awesome-zig)
- [Awesome Zig 2](https://github.com/nrdmn/awesome-zig)
- [Zig Learning & Usage Guide](https://github.com/C-BJ/awesome-zig)
- [Interview with Zig language creator Andrew Kelley (2020)](https://www.youtube.com/watch?v=ZvskDoP09Ao) ([HN](https://news.ycombinator.com/item?id=24292437))
- [What is Zig's Comptime? (2019)](https://kristoff.it/blog/what-is-zig-comptime/)
- [Zig's New Relationship with LLVM (2020)](https://kristoff.it/blog/zig-new-relationship-llvm/) ([HN](https://news.ycombinator.com/item?id=24615916)) ([Lobsters](https://lobste.rs/s/flw8du/zig_s_new_relationship_with_llvm))
- [Zig Compiler September Update & Hot Code Swapping Brainstorming (2020)](https://www.youtube.com/watch?v=3hwQSjhNSRU)
- [Advanced Hello World in Zig - Loris Cro (2020)](https://www.youtube.com/watch?v=iZFXAN8kpPo)
- [Zig heading toward a self-hosting compiler (2020)](https://lwn.net/Articles/833400/)
- [Assorted thoughts on zig (and rust) (2020)](https://scattered-thoughts.net/writing/assorted-thoughts-on-zig-and-rust/) ([Lobsters](https://lobste.rs/s/4hx42h/assorted_thoughts_on_zig_rust)) ([HN](https://news.ycombinator.com/item?id=24835357))
- [Is Zig the Long Awaited C Replacement? (2020)](https://erik-engheim.medium.com/is-zig-the-long-awaited-c-replacement-c8eeace1e692) ([Lobsters](https://lobste.rs/s/nrabd5/is_zig_long_awaited_c_replacement))
- [zigup](https://github.com/marler8997/zigup) - Download and manage zig compilers.
- [Zig Spec](https://github.com/ziglang/zig-spec)
- [Pirates of Apple Silicon - Jakub Konka, Frank Denis, Andrew Kelley (2020)](https://www.youtube.com/watch?v=t1pdnQRPAZo)
- [Zig in 30 Minutes](https://gist.github.com/ityonemo/769532c2017ed9143f3571e5ac104e50) ([HN](https://news.ycombinator.com/item?id=25618302))
- [Extending C with Zig](https://www.nmichaels.org/zig/c-library.html)
- [Why Zig when there is already C++, D, and Rust?](https://ziglang.org/learn/why_zig_rust_d_cpp/) ([HN](https://news.ycombinator.com/item?id=25797025))
- [Zig Makes Go Cross Compilation Just Work (2021)](https://dev.to/kristoff_it/zig-makes-go-cross-compilation-just-work-29ho) ([Lobsters](https://lobste.rs/s/4dejov/zig_makes_go_cross_compilation_just_work))
- [Ziglings](https://github.com/ratfactor/ziglings) - Learn the Zig programming language by fixing tiny broken programs. ([HN](https://news.ycombinator.com/item?id=26125063)) ([Stream doing Ziglings](https://github.com/achou11/ziglings-stream))
- [Zig Docs](https://ziglang.org/documentation/master/)
- [Zig Roadmap 2021](https://www.youtube.com/watch?v=pacsngNYXI0) ([Lobsters](https://lobste.rs/s/xdyrgj/zig_roadmap_2021))
- [Why I rewrote my Rust keyboard firmware in Zig: consistency, mastery, and fun (2021)](https://kevinlynagh.com/rust-zig/) ([Lobsters](https://lobste.rs/s/eppfav/why_i_rewrote_my_rust_keyboard_firmware))
- [Memory-mapped IO registers in zig (2021)](https://scattered-thoughts.net/writing/mmio-in-zig/) ([Lobsters](https://lobste.rs/s/46xhdl/memory_mapped_io_registers_zig))
- [Zig, Parser Combinators - and Why They're Awesome (2021)](https://devlog.hexops.com/2021/zig-parser-combinators-and-why-theyre-awesome)
- [How Safe Is Zig?](https://scattered-thoughts.net/writing/how-safe-is-zig/) ([Lobsters](https://lobste.rs/s/v5y4jb/how_safe_is_zig)) ([HN](https://news.ycombinator.com/item?id=26537693))
- [Zig Playground](https://zig-play-a9lwj.ondigitalocean.app/) - Online Zig compiler inspired by Go and Rust. ([Code](https://github.com/gsquire/zig-play))
- [zigdoc](https://github.com/g-w1/zigdoc) - zig -> docs.
- [zig.run](https://zig.run/) - Run and play with Zig source code. ([Code](https://github.com/jlauman/zig.run))
- [An intro to Zig's integer casting for C programmers](https://www.lagerdata.com/articles/an-intro-to-zigs-integer-casting-for-c-programmers) ([HN](https://news.ycombinator.com/item?id=27115551))
- [Performance Tracking for Zig](https://github.com/ziglang/gotta-go-fast)
- [Building an efficient and portable programming language with Zig (2021)](https://www.fastly.com/blog/building-an-efficient-and-portable-programming-language-with-zig) ([Lobsters](https://lobste.rs/s/qv9fgc/building_efficient_portable))
- [Zig Makes Rust Cross-compilation Just Work (2021)](https://actually.fyi/posts/zig-makes-rust-cross-compilation-just-work/) ([HN](https://news.ycombinator.com/item?id=27245369)) ([Lobsters](https://lobste.rs/s/nkalmb/zig_makes_rust_cross_compilation_just))
- [setup-zig](https://github.com/goto-bus-stop/setup-zig) - Use the Zig compiler in your Github Actions workflows.
- [Corecursive: Andrew Kelly Built Zig (2021)](https://corecursive.com/067-zig-with-andrew-kelley/) ([Reddit](https://www.reddit.com/r/programming/comments/owe4zl/fulltime_open_source_how_andrew_kelly_built_zig/)) ([HN](https://news.ycombinator.com/item?id=28046256))
- [Zig wrinkles (2021)](https://dev.to/stein/zig-dangers-confusions-and-annoyances-280h) ([Lobsters](https://lobste.rs/s/4pz3qg/zig_wrinkles))
- [Zig pathtracer (2021)](http://msinilo.pl/blog2/post/zig-pathtracer/) ([HN](https://news.ycombinator.com/item?id=28114957))
- [Async engines in C++20, Rust, & Zig (2021)](https://www.youtube.com/watch?v=Ws3jC6AJC_4)
- [Android Apps in Zig](https://github.com/MasterQ32/ZigAndroidTemplate) - Contains a example on how to create a minimal Android app in Zig.
- [Looking into Odin and Zig (2021)](https://ayende.com/blog/194466-A/looking-into-odin-and-zig-my-notes) ([HN](https://news.ycombinator.com/item?id=28440579))
- [Maintain It with Zig (2021)](https://kristoff.it/blog/maintain-it-with-zig/) ([HN](https://news.ycombinator.com/item?id=28458713)) ([Lobsters](https://lobste.rs/s/a9ghhz/maintain_it_with_zig))
- [ziglint](https://github.com/nektro/ziglint) - Linting suite for Zig.
- [Resource efficient Thread Pools with Zig (2021)](https://zig.news/kprotty/resource-efficient-thread-pools-with-zig-3291) ([HN](https://news.ycombinator.com/item?id=28509073))
- [Zig News](https://zig.news/)
- [Code Coverage for Zig with Callgrind (2021)](https://www.ryanliptak.com/blog/code-coverage-zig-callgrind/)
- [Fuzzing Zig Code Using AFL++ (2021)](https://www.ryanliptak.com/blog/fuzzing-zig-code/) ([HN](https://news.ycombinator.com/item?id=28600050))
- [Building gamedev ecosystem for Zig](https://github.com/michal-z/zig-gamedev)
- [Asserting function signatures at compile time in Zig (2021)](https://www.mdaverde.com/posts/zig-asserting-fn-types/)
- [Mach Engine: The Future of Graphics (With Zig) (2021)](https://devlog.hexops.com/2021/mach-engine-the-future-of-graphics-with-zig) ([HN](https://news.ycombinator.com/item?id=28909786)) ([Code](https://github.com/hexops/mach))
- [Andrew Kelley, Lead Developer & President of the Zig Software Foundation (2021)](https://overcast.fm/+cV8pJX6iU)
- [zig-snapshots](https://github.com/kubkon/zig-snapshots) - Preview Zig's incremental linker state in interactive HTML.
- [Zig LSP](https://github.com/ziglibs/zig-lsp) - LSP implemented in Zig.
- [Perfecting GLFW for Zig, and finding lurking undefined behavior that went unnot (2021)](https://devlog.hexops.com/2021/perfecting-glfw-for-zig-and-finding-undefined-behavior) ([HN](https://news.ycombinator.com/item?id=29060200))
- [Zig monthly](https://zigmonthly.org/) - Once-a-month publication where I curate all things Zig.
- [zig build explained (2021)](https://zig.news/xq/zig-build-explained-part-1-59lf)
- [A Practical Guide to Applying Data-Oriented Design - Andrew Kelley (2021)](https://media.handmade-seattle.com/practical-data-oriented-design/) ([Lobsters](https://lobste.rs/s/vbiu6y/practical_guide_applying_data_oriented))
- [The ZLD Linker (2021)](https://media.handmade-seattle.com/zld/)
- [Interfacing with Zig, a BDFL-run project (2021)](https://kristoff.it/blog/interfacing-with-zig/)
- [Nix flake for Zig](https://github.com/arqv/zig-overlay)
- [Zig Compiler Internals](https://github.com/mikdusan/zig.internals/blob/master/internals.rst)
- [Allocgate: Restructuring how allocators work in Zig (2021)](https://pithlessly.github.io/allocgate.html) ([HN](https://news.ycombinator.com/item?id=29571133))
- [List of Zig Gamedev Projects](https://github.com/ValorZard/awesome-zig-gamedev)
- [Minimal build.zig for targeting iOS](https://github.com/kubkon/zig-ios-example)
- [Zig 0.9.0](https://ziglang.org/download/0.9.0/release-notes.html) ([HN](https://news.ycombinator.com/item?id=29631202))
- [What do you think about Zig? (2021)](https://www.reddit.com/r/rust/comments/rlj9zl/what_do_you_think_about_zig/)
- [A Review of the Zig Programming Language (Using Advent of Code 2021)](https://www.duskborn.com/posts/2021-aoc-zig/) ([HN](https://news.ycombinator.com/item?id=29702607))
- [A Comparison of Rust and Zig](https://expandingman.gitlab.io/tvu-compare/) ([HN](https://news.ycombinator.com/item?id=29762988))
- [Analysis of the overhead of a minimal Zig program (2022)](https://zig.news/aransentin/analysis-of-the-overhead-of-a-minimal-zig-program-4lg0) ([Lobsters](https://lobste.rs/s/hbceut/analysis_overhead_minimal_zig_program))
- [Zig Strings in 5 minutes](https://www.huy.rocks/everyday/01-04-2022-zig-strings-in-5-minutes) ([Lobsters](https://lobste.rs/s/nimeia/zig_strings_5_minutes))
- [Failing to Learn Zig via Advent of Code (2022)](https://www.forrestthewoods.com/blog/failing-to-learn-zig-via-advent-of-code/) ([HN](https://news.ycombinator.com/item?id=29965239)) ([Lobsters](https://lobste.rs/s/or1fr4/failing_learn_zig_via_advent_code))
- [Let's build an Entity Component System from scratch in Zig (2022)](https://devlog.hexops.com/2022/lets-build-ecs-part-1)
- [Using Zig to Build Native Lua Scripts (2022)](https://cone.codes/posts/using-zig-to-build-native-lua-scripts/)
- [Zig by Example](https://zig-by-example.com/) ([Code](https://github.com/ibokuri/zig-by-example))
- [Zig Compiler Internals](https://mitchellh.com/zig) ([HN](https://news.ycombinator.com/item?id=30470442))
- [Is Zig faster than Rust?](https://users.rust-lang.org/t/is-zig-lang-faster-than-rust/70390)
- [Why use Zig over Rust/Go (2022)](https://www.reddit.com/r/Zig/comments/srk7ws/im_still_confused_on_the_whys_of_zig/)
- [ziglibc](https://github.com/marler8997/ziglibc) - Exploration on creating a libc implementation in Zig.
- [Using Zig as cross-platform C toolchain (2022)](https://ruoyusun.com/2022/02/27/zig-cc.html) ([HN](https://news.ycombinator.com/item?id=30488979))
- [ZigSelf: An implementation of Self in Zig](https://sin-ack.github.io/posts/zigself-01/) ([Lobsters](https://lobste.rs/s/ggwzjq/zigself_implementation_self_zig))
- [zigtool](https://github.com/dosgo/zigtool) - Go tool of the zig compiler automatically compiles different targets according to the GOOS GOARCH environment variable.
- [Hot-code reloading on macOS/arm64 with Zig (2022)](http://www.jakubkonka.com/2022/03/16/hcs-zig.html) ([HN](https://news.ycombinator.com/item?id=30716177))
- [wazm](https://github.com/fengb/wazm) - Web Assembly Zig Machine.
- [Looking at Zig Programming Language (2022)](https://codecs.multimedia.cx/2022/02/looking-at-zig-programming-language/) ([HN](https://news.ycombinator.com/item?id=30919305))
- [I Believe Zig Has Function Colors (2022)](https://gavinhoward.com/2022/04/i-believe-zig-has-function-colors/) ([Lobsters](https://lobste.rs/s/mw1f3s/i_believe_zig_has_function_colors)) ([HN](https://news.ycombinator.com/item?id=30965805))
- [Zig Bit Twiddling Hacks](https://github.com/cryptocode/bithacks)
- [Zig self-hosted compiler can now build itself (2022)](https://github.com/ziglang/zig/pull/11442) ([HN](https://news.ycombinator.com/item?id=31052029)) ([Lobsters](https://lobste.rs/s/0j45v4/zig_self_hosted_compiler_can_now_build))
- [Zig interpreter written in TypeScript](https://github.com/mbrock/zigjs)
- [Zig Web Code](https://github.com/ziglang/www.ziglang.org)
- [Getting Started with Zig on the Raspberry Pi Pico](https://github.com/ZigEmbeddedGroup/getting-started-pico-zig)
- [Minimal example showing how HTML5's canvas, WASM memory and Zig can interact](https://github.com/daneelsan/minimal-zig-wasm-canvas)
- [Uber Uses Zig (2022)](https://jakstys.lt/2022/how-uber-uses-zig/) ([HN](https://news.ycombinator.com/item?id=31478562)) ([Lobsters](https://lobste.rs/s/l9ghdb/how_zig_is_used_at_uber))
- [Zig PyPI distribution](https://github.com/ziglang/zig-pypi) - Zig programming language, packaged for PyPI. Lets you run Zig code from Python easily. ([Tweet](https://twitter.com/simonw/status/1528742284241408001))
