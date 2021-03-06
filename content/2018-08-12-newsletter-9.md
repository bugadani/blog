+++
title = "The Embedded Working Group Newsletter - 9"
date = 2018-08-12
draft = false
in_search_index = true
template = "page.html"
aliases = ["2018-08-12/"]
+++

This is the ninth newsletter of the [Embedded WG] where we highlight new progress, celebrate cool projects, thank the community, and advertise projects that need help!

<!-- more -->

If you want to mention something in [the next newsletter], make sure to leave a comment on the issue.

[the next newsletter]: https://github.com/rust-embedded/wg/issues/164
[Embedded WG]: https://github.com/rust-embedded/wg

## Highlights

* The Embedded Working Group has moved! You can find our new coordination repo at [rust-embedded/wg] on GitHub, and crates maintained by the working group in the [rust-embedded] organization
* The Embedded Working Group has grown! We are now 18 people grouped in the following 6 teams to allow for better focus on these topics:
    * The **Cortex-M** team develops and maintains the core of the Cortex-M crate ecosystem
    * The **HAL team** develops and maintains crates that ease the development of Hardware Abstraction Layers, Board Support Crates and drivers
    * The **MS430 team** develops and maintains the core of the MSP430 crate ecosystem
    * The **RISCV team** develops and maintains the core of the RISCV crate ecosystem
    * The **Resources team** develops, maintains and curates resources on embedded Rust
    * The **Tools team** maintains and develops core embedded tools

[rust-embedded/wg]: https://github.com/rust-embedded/wg
[rust-embedded]: https://github.com/rust-embedded

## Embedded Projects

If you have an embedded project or blog post you would like to have featured in the Embedded WG Newsletter, make sure to mention it on the tracking issue for [the next newsletter], we would love to show it off!

* [rust-lang/rust#52787] has landed, adding support in `nightly` for the RISC-V architecture as a bare-metal target!

[rust-lang/rust#52787]: https://github.com/rust-lang/rust/pull/52787

### `embedded-hal` Ecosystem Crates

As part of the [Weekly Driver Initiative], crates that are part of the `embedded-hal` ecosystem are now tracked in the [Awesome Embedded Rust] repository. Here is a current snapshot of what is available there:

| Type                      | Status    | Count | Diff |
| :---                      | :-----    | :---- | :--- |
| [Device Crates]           | released  | 14    | 0    |
| [HAL Impl Crates]         | released  | 11    | 0    |
| [Board Support Crates]    | released  | 9     | +1   |
| [Driver Crates Released]  | released  | 11    | 0    |
| [Driver Crates WIP]       | WIP       | 38    | +3   |
| [no-std crates]           | released  | 12    | 0    |

[Awesome Embedded Rust]: https://github.com/rust-embedded/awesome-embedded-rust
[Weekly Driver Initiative]: https://github.com/rust-lang-nursery/embedded-wg/issues/39
[Device Crates]: https://github.com/rust-embedded/awesome-embedded-rust#device-crates
[HAL Impl Crates]: https://github.com/rust-embedded/awesome-embedded-rust#hal-implementation-crates
[Board Support Crates]: https://github.com/rust-embedded/awesome-embedded-rust#board-support-crates
[Driver Crates Released]: https://github.com/rust-embedded/awesome-embedded-rust#driver-crates
[Driver Crates WIP]: https://github.com/rust-embedded/awesome-embedded-rust#wip
[no-std crates]: https://github.com/rust-embedded/awesome-embedded-rust#no-std-crates

## Help Wanted

* We're considering changing to LLD as the default linker for `thumb` targets. Check out the RFC at [rust-embedded/wg#160], and let us know what you think

[rust-embedded/wg#160]: https://github.com/rust-embedded/wg/issues/160
