# Third-Party Notices

Generated from the locked Apple Silicon (`aarch64-apple-darwin`) runtime dependency graph and the installed production WebView packages. Build, test, lint, type-check, and release-only tools are excluded. Every component below is unmodified unless explicitly stated otherwise.

Runtime dependency count: 192 (188 Rust/Tauri, 4 WebView).

Quota Float reference: Codex Glance independently reimplemented only the general draggable, always-on-top window concept after reviewing the MIT-licensed Quota Float repository (https://github.com/change-42-yhmm/quota-float). No Quota Float source code, authentication logic, supporter features, skins, or private quota integration is included or distributed.

## Production WebView dependencies

| Component | Version | Relationship | Declared SPDX | Copyright / author | Source | Use in application | Modified | Included license text |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| @tauri-apps/api | 2.11.1 | Production WebView dependency | MIT OR Apache-2.0 | Tauri Programme within The Commons Conservancy | npm registry | Tauri JavaScript bridge used by the production WebView | No | MIT |
| react | 19.2.8 | Production WebView dependency | MIT | Meta Platforms, Inc. and affiliates | npm registry | Production user interface runtime | No | MIT |
| react-dom | 19.2.8 | Production WebView dependency | MIT | Meta Platforms, Inc. and affiliates | npm registry | Production React DOM renderer | No | MIT |
| scheduler | 0.27.0 | Production WebView dependency | MIT | Meta Platforms, Inc. and affiliates | npm registry | React scheduling runtime | No | MIT |

## Rust and Tauri runtime dependencies

| Component | Version | Relationship | Declared SPDX | Copyright / author | Source | Use in application | Modified | Included license text |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| adler2 | 2.0.1 | Transitive Rust dependency | 0BSD OR MIT OR Apache-2.0 | Jonas Schievink, oyvindln | https://github.com/oyvindln/adler2 | Tauri/native runtime dependency | No | MIT |
| aho-corasick | 1.1.4 | Transitive Rust dependency | Unlicense OR MIT | Andrew Gallant | https://github.com/BurntSushi/aho-corasick | Tauri/native runtime dependency | No | MIT |
| alloc-no-stdlib | 2.0.4 | Transitive Rust dependency | BSD-3-Clause | Daniel Reiter Horn | https://github.com/dropbox/rust-alloc-no-stdlib | Tauri/native runtime dependency | No | BSD-3-Clause |
| alloc-stdlib | 0.2.4 | Transitive Rust dependency | BSD-3-Clause | Daniel Reiter Horn | https://github.com/dropbox/rust-alloc-no-stdlib | Tauri/native runtime dependency | No | BSD-3-Clause |
| anyhow | 1.0.104 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/anyhow | Tauri/native runtime dependency | No | MIT |
| base64 | 0.21.7 | Transitive Rust dependency | MIT OR Apache-2.0 | Alice Maz, Marshall Pierce | https://github.com/marshallpierce/rust-base64 | Tauri/native runtime dependency | No | MIT |
| base64 | 0.22.1 | Transitive Rust dependency | MIT OR Apache-2.0 | Marshall Pierce | https://github.com/marshallpierce/rust-base64 | Tauri/native runtime dependency | No | MIT |
| bit-set | 0.8.0 | Transitive Rust dependency | Apache-2.0 OR MIT | Alexis Beingessner | https://github.com/contain-rs/bit-set | Tauri/native runtime dependency | No | MIT |
| bit-vec | 0.8.0 | Transitive Rust dependency | Apache-2.0 OR MIT | Alexis Beingessner | https://github.com/contain-rs/bit-vec | Tauri/native runtime dependency | No | MIT |
| bitflags | 2.13.1 | Transitive Rust dependency | MIT OR Apache-2.0 | The Rust Project Developers | https://github.com/bitflags/bitflags | Tauri/native runtime dependency | No | MIT |
| block2 | 0.6.2 | Transitive Rust dependency | MIT | Mads Marquart | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| brotli | 8.0.4 | Transitive Rust dependency | BSD-3-Clause AND MIT | Daniel Reiter Horn, The Brotli Authors | https://github.com/dropbox/rust-brotli | Tauri/native runtime dependency | No | BSD-3-Clause + MIT |
| brotli-decompressor | 5.0.3 | Transitive Rust dependency | BSD-3-Clause/MIT | Daniel Reiter Horn, The Brotli Authors | https://github.com/dropbox/rust-brotli-decompressor | Tauri/native runtime dependency | No | BSD-3-Clause + MIT |
| bs58 | 0.5.1 | Transitive Rust dependency | MIT/Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/Nullus157/bs58-rs | Tauri/native runtime dependency | No | MIT |
| byteorder | 1.5.0 | Transitive Rust dependency | Unlicense OR MIT | Andrew Gallant | https://github.com/BurntSushi/byteorder | Tauri/native runtime dependency | No | MIT |
| bytes | 1.12.1 | Transitive Rust dependency | MIT | Carl Lerche, Sean McArthur | https://github.com/tokio-rs/bytes | Tauri/native runtime dependency | No | MIT |
| camino | 1.2.4 | Transitive Rust dependency | MIT OR Apache-2.0 | Without Boats, Ashley Williams, Steve Klabnik, Rain | https://github.com/camino-rs/camino | Tauri/native runtime dependency | No | MIT |
| cargo_metadata | 0.19.2 | Transitive Rust dependency | MIT | Oliver Schneider | https://github.com/oli-obk/cargo_metadata | Tauri/native runtime dependency | No | MIT |
| cargo-platform | 0.1.9 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/rust-lang/cargo | Tauri/native runtime dependency | No | MIT |
| cfb | 0.7.3 | Transitive Rust dependency | MIT | Matthew D. Steele | https://github.com/mdsteele/rust-cfb | Tauri/native runtime dependency | No | MIT |
| cfg-if | 1.0.4 | Transitive Rust dependency | MIT OR Apache-2.0 | Alex Crichton | https://github.com/rust-lang/cfg-if | Tauri/native runtime dependency | No | MIT |
| chrono | 0.4.45 | Direct Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/chronotope/chrono | Tauri/native runtime dependency | No | MIT |
| cookie | 0.18.1 | Transitive Rust dependency | MIT OR Apache-2.0 | Sergio Benitez, Alex Crichton | https://github.com/SergioBenitez/cookie-rs | Tauri/native runtime dependency | No | MIT |
| core-foundation | 0.10.1 | Transitive Rust dependency | MIT OR Apache-2.0 | The Servo Project Developers | https://github.com/servo/core-foundation-rs | Tauri/native runtime dependency | No | MIT |
| core-foundation-sys | 0.8.7 | Transitive Rust dependency | MIT OR Apache-2.0 | The Servo Project Developers | https://github.com/servo/core-foundation-rs | Tauri/native runtime dependency | No | MIT |
| core-graphics | 0.25.0 | Transitive Rust dependency | MIT OR Apache-2.0 | The Servo Project Developers | https://github.com/servo/core-foundation-rs | Tauri/native runtime dependency | No | MIT |
| core-graphics-types | 0.2.0 | Transitive Rust dependency | MIT OR Apache-2.0 | The Servo Project Developers | https://github.com/servo/core-foundation-rs | Tauri/native runtime dependency | No | MIT |
| crc32fast | 1.5.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Sam Rijs, Alex Crichton | https://github.com/srijs/rust-crc32fast | Tauri/native runtime dependency | No | MIT |
| crossbeam-channel | 0.5.16 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/crossbeam-rs/crossbeam | Tauri/native runtime dependency | No | MIT |
| crossbeam-utils | 0.8.22 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/crossbeam-rs/crossbeam | Tauri/native runtime dependency | No | MIT |
| cssparser | 0.36.0 | Transitive Rust dependency | MPL-2.0 | Simon Sapin | https://github.com/servo/rust-cssparser | Tauri/native runtime dependency | No | MPL-2.0 |
| ctor | 0.8.0 | Transitive Rust dependency | Apache-2.0 OR MIT | Matt Mastracci | https://github.com/mmastrac/rust-ctor | Tauri/native runtime dependency | No | MIT |
| deranged | 0.5.8 | Transitive Rust dependency | MIT OR Apache-2.0 | Jacob Pratt | https://github.com/jhpratt/deranged | Tauri/native runtime dependency | No | MIT |
| derive_more | 2.1.1 | Transitive Rust dependency | MIT | Jelte Fennema | https://github.com/JelteF/derive_more | Tauri/native runtime dependency | No | MIT |
| dirs | 6.0.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Simon Ochsenreither | https://github.com/soc/dirs-rs | Tauri/native runtime dependency | No | MIT |
| dirs-sys | 0.5.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Simon Ochsenreither | https://github.com/dirs-dev/dirs-sys-rs | Tauri/native runtime dependency | No | MIT |
| dispatch2 | 0.3.1 | Transitive Rust dependency | Zlib OR Apache-2.0 OR MIT | Mads Marquart, Mary | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| dom_query | 0.27.0 | Transitive Rust dependency | MIT | niklak, importcjj | https://github.com/niklak/dom_query | Tauri/native runtime dependency | No | MIT |
| dpi | 0.1.2 | Transitive Rust dependency | Apache-2.0 AND MIT | Not specified in crate metadata; package license text retained | https://github.com/rust-windowing/winit | Tauri/native runtime dependency | No | Apache-2.0 + MIT |
| dtoa | 1.0.11 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/dtoa | Tauri/native runtime dependency | No | MIT |
| dtoa-short | 0.3.5 | Transitive Rust dependency | MPL-2.0 | Xidorn Quan | https://github.com/upsuper/dtoa-short | Tauri/native runtime dependency | No | MPL-2.0 |
| dtor | 0.3.0 | Transitive Rust dependency | Apache-2.0 OR MIT | Matt Mastracci | https://github.com/mmastrac/rust-ctor | Tauri/native runtime dependency | No | MIT |
| dunce | 1.0.5 | Transitive Rust dependency | CC0-1.0 OR MIT-0 OR Apache-2.0 | Kornel | https://gitlab.com/kornelski/dunce | Tauri/native runtime dependency | No | MIT |
| dyn-clone | 1.0.20 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/dyn-clone | Tauri/native runtime dependency | No | MIT |
| embed_plist | 1.2.2 | Transitive Rust dependency | MIT OR Apache-2.0 | Nikolai Vazquez | https://github.com/nvzqz/embed-plist-rs | Tauri/native runtime dependency | No | MIT |
| equivalent | 1.0.2 | Transitive Rust dependency | Apache-2.0 OR MIT | Not specified in crate metadata; package license text retained | https://github.com/indexmap-rs/equivalent | Tauri/native runtime dependency | No | MIT |
| erased-serde | 0.4.10 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/erased-serde | Tauri/native runtime dependency | No | MIT |
| fdeflate | 0.3.7 | Transitive Rust dependency | MIT OR Apache-2.0 | The image-rs Developers | https://github.com/image-rs/fdeflate | Tauri/native runtime dependency | No | MIT |
| flate2 | 1.1.9 | Transitive Rust dependency | MIT OR Apache-2.0 | Alex Crichton, Josh Triplett | https://github.com/rust-lang/flate2-rs | Tauri/native runtime dependency | No | MIT |
| fnv | 1.0.7 | Transitive Rust dependency | Apache-2.0 / MIT | Alex Crichton | https://github.com/servo/rust-fnv | Tauri/native runtime dependency | No | Apache-2.0 + MIT |
| foldhash | 0.2.0 | Transitive Rust dependency | Zlib | Orson Peters | https://github.com/orlp/foldhash | Tauri/native runtime dependency | No | Zlib |
| foreign-types | 0.5.0 | Transitive Rust dependency | MIT/Apache-2.0 | Steven Fackler | https://github.com/sfackler/foreign-types | Tauri/native runtime dependency | No | MIT |
| foreign-types-shared | 0.3.1 | Transitive Rust dependency | MIT/Apache-2.0 | Steven Fackler | https://github.com/sfackler/foreign-types | Tauri/native runtime dependency | No | MIT |
| form_urlencoded | 1.2.2 | Transitive Rust dependency | MIT OR Apache-2.0 | The rust-url developers | https://github.com/servo/rust-url | Tauri/native runtime dependency | No | MIT |
| getrandom | 0.3.4 | Transitive Rust dependency | MIT OR Apache-2.0 | The Rand Project Developers | https://github.com/rust-random/getrandom | Tauri/native runtime dependency | No | MIT |
| getrandom | 0.4.3 | Transitive Rust dependency | MIT OR Apache-2.0 | The Rand Project Developers | https://github.com/rust-random/getrandom | Tauri/native runtime dependency | No | MIT |
| glob | 0.3.4 | Transitive Rust dependency | MIT OR Apache-2.0 | The Rust Project Developers | https://github.com/rust-lang/glob | Tauri/native runtime dependency | No | MIT |
| hashbrown | 0.12.3 | Transitive Rust dependency | MIT OR Apache-2.0 | Amanieu d'Antras | https://github.com/rust-lang/hashbrown | Tauri/native runtime dependency | No | MIT |
| hashbrown | 0.17.1 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/rust-lang/hashbrown | Tauri/native runtime dependency | No | MIT |
| heck | 0.5.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/withoutboats/heck | Tauri/native runtime dependency | No | MIT |
| hex | 0.4.3 | Transitive Rust dependency | MIT OR Apache-2.0 | KokaKiwi | https://github.com/KokaKiwi/rust-hex | Tauri/native runtime dependency | No | MIT |
| html5ever | 0.38.0 | Transitive Rust dependency | MIT OR Apache-2.0 | The html5ever Project Developers | https://github.com/servo/html5ever | Tauri/native runtime dependency | No | MIT |
| http | 1.4.2 | Transitive Rust dependency | MIT OR Apache-2.0 | Alex Crichton, Carl Lerche, Sean McArthur | https://github.com/hyperium/http | Tauri/native runtime dependency | No | MIT |
| iana-time-zone | 0.1.65 | Transitive Rust dependency | MIT OR Apache-2.0 | Andrew Straw, René Kijewski, Ryan Lopopolo | https://github.com/strawlab/iana-time-zone | Tauri/native runtime dependency | No | MIT |
| icu_collections | 2.2.0 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| icu_locale_core | 2.2.0 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| icu_normalizer | 2.2.0 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| icu_normalizer_data | 2.2.0 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| icu_properties | 2.2.0 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| icu_properties_data | 2.2.0 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| icu_provider | 2.2.0 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| idna | 1.1.0 | Transitive Rust dependency | MIT OR Apache-2.0 | The rust-url developers | https://github.com/servo/rust-url/ | Tauri/native runtime dependency | No | MIT |
| idna_adapter | 1.2.2 | Transitive Rust dependency | Apache-2.0 OR MIT | The rust-url developers | https://github.com/hsivonen/idna_adapter | Tauri/native runtime dependency | No | MIT |
| indexmap | 1.9.3 | Transitive Rust dependency | Apache-2.0 OR MIT | Not specified in crate metadata; package license text retained | https://github.com/bluss/indexmap | Tauri/native runtime dependency | No | MIT |
| indexmap | 2.14.0 | Transitive Rust dependency | Apache-2.0 OR MIT | Not specified in crate metadata; package license text retained | https://github.com/indexmap-rs/indexmap | Tauri/native runtime dependency | No | MIT |
| infer | 0.19.0 | Transitive Rust dependency | MIT | Bojan | https://github.com/bojand/infer | Tauri/native runtime dependency | No | MIT |
| itoa | 1.0.18 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/itoa | Tauri/native runtime dependency | No | MIT |
| json-patch | 3.0.1 | Transitive Rust dependency | MIT/Apache-2.0 | Ivan Dubrov | https://github.com/idubrov/json-patch | Tauri/native runtime dependency | No | MIT |
| jsonptr | 0.6.3 | Transitive Rust dependency | MIT OR Apache-2.0 | chance dinkins, André Sá de Mello | https://github.com/chanced/jsonptr | Tauri/native runtime dependency | No | MIT |
| keyboard-types | 0.7.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Pyfisch | https://github.com/pyfisch/keyboard-types | Tauri/native runtime dependency | No | MIT |
| libc | 0.2.189 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/rust-lang/libc | Tauri/native runtime dependency | No | MIT |
| litemap | 0.8.2 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| lock_api | 0.4.14 | Transitive Rust dependency | MIT OR Apache-2.0 | Amanieu d'Antras | https://github.com/Amanieu/parking_lot | Tauri/native runtime dependency | No | MIT |
| log | 0.4.33 | Transitive Rust dependency | MIT OR Apache-2.0 | The Rust Project Developers | https://github.com/rust-lang/log | Tauri/native runtime dependency | No | MIT |
| markup5ever | 0.38.0 | Transitive Rust dependency | MIT OR Apache-2.0 | The html5ever Project Developers | https://github.com/servo/html5ever | Tauri/native runtime dependency | No | MIT |
| memchr | 2.8.3 | Transitive Rust dependency | Unlicense OR MIT | Andrew Gallant, bluss | https://github.com/BurntSushi/memchr | Tauri/native runtime dependency | No | MIT |
| mime | 0.3.17 | Transitive Rust dependency | MIT OR Apache-2.0 | Sean McArthur | https://github.com/hyperium/mime | Tauri/native runtime dependency | No | MIT |
| miniz_oxide | 0.8.9 | Transitive Rust dependency | MIT OR Zlib OR Apache-2.0 | Frommi, oyvindln, Rich Geldreich | https://github.com/Frommi/miniz_oxide/tree/master/miniz_oxide | Tauri/native runtime dependency | No | MIT |
| mio | 1.2.2 | Transitive Rust dependency | MIT | Carl Lerche, Thomas de Zeeuw, Tokio Contributors | https://github.com/tokio-rs/mio | Tauri/native runtime dependency | No | MIT |
| muda | 0.19.3 | Transitive Rust dependency | Apache-2.0 OR MIT | Not specified in crate metadata; package license text retained | https://github.com/tauri-apps/muda | Tauri/native runtime dependency | No | MIT |
| new_debug_unreachable | 1.0.6 | Transitive Rust dependency | MIT | Matt Brubeck, Jonathan Reem | https://github.com/mbrubeck/rust-debug-unreachable | Tauri/native runtime dependency | No | MIT |
| num-conv | 0.2.2 | Transitive Rust dependency | MIT OR Apache-2.0 | Jacob Pratt | https://github.com/jhpratt/num-conv | Tauri/native runtime dependency | No | MIT |
| num-traits | 0.2.19 | Transitive Rust dependency | MIT OR Apache-2.0 | The Rust Project Developers | https://github.com/rust-num/num-traits | Tauri/native runtime dependency | No | MIT |
| objc2 | 0.6.4 | Transitive Rust dependency | MIT | Mads Marquart | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| objc2-app-kit | 0.3.2 | Transitive Rust dependency | Zlib OR Apache-2.0 OR MIT | Not specified in crate metadata; package license text retained | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| objc2-core-foundation | 0.3.2 | Transitive Rust dependency | Zlib OR Apache-2.0 OR MIT | Not specified in crate metadata; package license text retained | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| objc2-core-graphics | 0.3.2 | Transitive Rust dependency | Zlib OR Apache-2.0 OR MIT | Not specified in crate metadata; package license text retained | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| objc2-encode | 4.1.0 | Transitive Rust dependency | MIT | Mads Marquart | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| objc2-exception-helper | 0.1.1 | Transitive Rust dependency | Zlib OR Apache-2.0 OR MIT | Mads Marquart | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| objc2-foundation | 0.3.2 | Transitive Rust dependency | MIT | Not specified in crate metadata; package license text retained | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| objc2-io-surface | 0.3.2 | Transitive Rust dependency | Zlib OR Apache-2.0 OR MIT | Not specified in crate metadata; package license text retained | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| objc2-web-kit | 0.3.2 | Transitive Rust dependency | Zlib OR Apache-2.0 OR MIT | Not specified in crate metadata; package license text retained | https://github.com/madsmtm/objc2 | Tauri/native runtime dependency | No | MIT |
| once_cell | 1.21.4 | Transitive Rust dependency | MIT OR Apache-2.0 | Aleksey Kladov | https://github.com/matklad/once_cell | Tauri/native runtime dependency | No | MIT |
| option-ext | 0.2.0 | Transitive Rust dependency | MPL-2.0 | Simon Ochsenreither | https://github.com/soc/option-ext.git | Tauri/native runtime dependency | No | MPL-2.0 |
| parking_lot | 0.12.5 | Transitive Rust dependency | MIT OR Apache-2.0 | Amanieu d'Antras | https://github.com/Amanieu/parking_lot | Tauri/native runtime dependency | No | MIT |
| parking_lot_core | 0.9.12 | Transitive Rust dependency | MIT OR Apache-2.0 | Amanieu d'Antras | https://github.com/Amanieu/parking_lot | Tauri/native runtime dependency | No | MIT |
| percent-encoding | 2.3.2 | Transitive Rust dependency | MIT OR Apache-2.0 | The rust-url developers | https://github.com/servo/rust-url/ | Tauri/native runtime dependency | No | MIT |
| phf | 0.13.1 | Transitive Rust dependency | MIT | Steven Fackler | https://github.com/rust-phf/rust-phf | Tauri/native runtime dependency | No | MIT |
| phf_shared | 0.13.1 | Transitive Rust dependency | MIT | Steven Fackler | https://github.com/rust-phf/rust-phf | Tauri/native runtime dependency | No | MIT |
| pin-project-lite | 0.2.17 | Transitive Rust dependency | Apache-2.0 OR MIT | Not specified in crate metadata; package license text retained | https://github.com/taiki-e/pin-project-lite | Tauri/native runtime dependency | No | MIT |
| plist | 1.10.0 | Transitive Rust dependency | MIT | Ed Barnard | https://github.com/ebarnard/rust-plist/ | Tauri/native runtime dependency | No | MIT |
| png | 0.18.1 | Transitive Rust dependency | MIT OR Apache-2.0 | The image-rs Developers | https://github.com/image-rs/image-png | Tauri/native runtime dependency | No | MIT |
| potential_utf | 0.1.5 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| powerfmt | 0.2.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Jacob Pratt | https://github.com/jhpratt/powerfmt | Tauri/native runtime dependency | No | MIT |
| precomputed-hash | 0.1.1 | Transitive Rust dependency | MIT | Emilio Cobos Álvarez | https://github.com/emilio/precomputed-hash | Tauri/native runtime dependency | No | MIT |
| proc-macro2 | 1.0.107 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay, Alex Crichton | https://github.com/dtolnay/proc-macro2 | Tauri/native runtime dependency | No | MIT |
| quick-xml | 0.41.0 | Transitive Rust dependency | MIT | Not specified in crate metadata; package license text retained | https://github.com/tafia/quick-xml | Tauri/native runtime dependency | No | MIT |
| quote | 1.0.47 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/quote | Tauri/native runtime dependency | No | MIT |
| raw-window-handle | 0.6.2 | Transitive Rust dependency | MIT OR Apache-2.0 OR Zlib | Osspial | https://github.com/rust-windowing/raw-window-handle | Tauri/native runtime dependency | No | MIT |
| ref-cast | 1.0.26 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/ref-cast | Tauri/native runtime dependency | No | MIT |
| regex | 1.13.1 | Transitive Rust dependency | MIT OR Apache-2.0 | The Rust Project Developers, Andrew Gallant | https://github.com/rust-lang/regex | Tauri/native runtime dependency | No | MIT |
| regex-automata | 0.4.16 | Transitive Rust dependency | MIT OR Apache-2.0 | The Rust Project Developers, Andrew Gallant | https://github.com/rust-lang/regex | Tauri/native runtime dependency | No | MIT |
| regex-syntax | 0.8.11 | Transitive Rust dependency | MIT OR Apache-2.0 | The Rust Project Developers, Andrew Gallant | https://github.com/rust-lang/regex | Tauri/native runtime dependency | No | MIT |
| rustc-hash | 2.1.3 | Transitive Rust dependency | Apache-2.0 OR MIT | The Rust Project Developers | https://github.com/rust-lang/rustc-hash | Tauri/native runtime dependency | No | MIT |
| same-file | 1.0.6 | Transitive Rust dependency | Unlicense/MIT | Andrew Gallant | https://github.com/BurntSushi/same-file | Tauri/native runtime dependency | No | MIT |
| schemars | 0.8.22 | Transitive Rust dependency | MIT | Graham Esau | https://github.com/GREsau/schemars | Tauri/native runtime dependency | No | MIT |
| schemars | 0.9.0 | Transitive Rust dependency | MIT | Graham Esau | https://github.com/GREsau/schemars | Tauri/native runtime dependency | No | MIT |
| schemars | 1.2.1 | Transitive Rust dependency | MIT | Graham Esau | https://github.com/GREsau/schemars | Tauri/native runtime dependency | No | MIT |
| scopeguard | 1.2.0 | Transitive Rust dependency | MIT OR Apache-2.0 | bluss | https://github.com/bluss/scopeguard | Tauri/native runtime dependency | No | MIT |
| selectors | 0.36.1 | Transitive Rust dependency | MPL-2.0 | The Servo Project Developers | https://github.com/servo/stylo | Tauri/native runtime dependency | No | MPL-2.0 |
| semver | 1.0.28 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/semver | Tauri/native runtime dependency | No | MIT |
| serde | 1.0.229 | Direct Rust dependency | MIT OR Apache-2.0 | Erick Tryzelaar, David Tolnay | https://github.com/serde-rs/serde | Tauri/native runtime dependency | No | MIT |
| serde_core | 1.0.229 | Transitive Rust dependency | MIT OR Apache-2.0 | Erick Tryzelaar, David Tolnay | https://github.com/serde-rs/serde | Tauri/native runtime dependency | No | MIT |
| serde_json | 1.0.151 | Direct Rust dependency | MIT OR Apache-2.0 | Erick Tryzelaar, David Tolnay | https://github.com/serde-rs/json | Tauri/native runtime dependency | No | MIT |
| serde_spanned | 1.1.1 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/toml-rs/toml | Tauri/native runtime dependency | No | MIT |
| serde_with | 3.21.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Jonas Bushart, Marcin Kaźmierczak | https://github.com/jonasbb/serde_with/ | Tauri/native runtime dependency | No | MIT |
| serde-untagged | 0.1.9 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/serde-untagged | Tauri/native runtime dependency | No | MIT |
| serialize-to-javascript | 0.1.2 | Transitive Rust dependency | MIT OR Apache-2.0 | Chip Reed | https://github.com/chippers/serialize-to-javascript | Tauri/native runtime dependency | No | MIT |
| servo_arc | 0.4.3 | Transitive Rust dependency | MIT OR Apache-2.0 | The Servo Project Developers | https://github.com/servo/stylo | Tauri/native runtime dependency | No | MIT |
| simd-adler32 | 0.3.10 | Transitive Rust dependency | MIT | Marvin Countryman | https://github.com/mcountryman/simd-adler32 | Tauri/native runtime dependency | No | MIT |
| siphasher | 1.0.3 | Transitive Rust dependency | MIT/Apache-2.0 | Frank Denis | https://github.com/jedisct1/rust-siphash | Tauri/native runtime dependency | No | MIT |
| smallvec | 1.15.2 | Transitive Rust dependency | MIT OR Apache-2.0 | The Servo Project Developers | https://github.com/servo/rust-smallvec | Tauri/native runtime dependency | No | MIT |
| socket2 | 0.6.5 | Transitive Rust dependency | MIT OR Apache-2.0 | Alex Crichton, Thomas de Zeeuw | https://github.com/rust-lang/socket2 | Tauri/native runtime dependency | No | MIT |
| stable_deref_trait | 1.2.1 | Transitive Rust dependency | MIT OR Apache-2.0 | Robert Grosse | https://github.com/storyyeller/stable_deref_trait | Tauri/native runtime dependency | No | MIT |
| string_cache | 0.9.0 | Transitive Rust dependency | MIT OR Apache-2.0 | The Servo Project Developers | https://github.com/servo/string-cache | Tauri/native runtime dependency | No | MIT |
| swift-rs | 1.0.7 | Transitive Rust dependency | MIT OR Apache-2.0 | The swift-rs contributors | https://github.com/Brendonovich/swift-rs | Tauri/native runtime dependency | No | MIT |
| tao | 0.35.3 | Transitive Rust dependency | Apache-2.0 | Tauri Programme within The Commons Conservancy, The winit contributors | https://github.com/tauri-apps/tao | Tauri/native runtime dependency | No | Apache-2.0 |
| tauri | 2.11.5 | Direct Rust dependency | Apache-2.0 OR MIT | Tauri Programme within The Commons Conservancy | https://github.com/tauri-apps/tauri | Tauri/native runtime dependency | No | MIT |
| tauri-runtime | 2.11.3 | Transitive Rust dependency | Apache-2.0 OR MIT | Tauri Programme within The Commons Conservancy | https://github.com/tauri-apps/tauri | Tauri/native runtime dependency | No | MIT |
| tauri-runtime-wry | 2.11.4 | Transitive Rust dependency | Apache-2.0 OR MIT | Tauri Programme within The Commons Conservancy | https://github.com/tauri-apps/tauri | Tauri/native runtime dependency | No | MIT |
| tauri-utils | 2.9.3 | Transitive Rust dependency | Apache-2.0 OR MIT | Tauri Programme within The Commons Conservancy | https://github.com/tauri-apps/tauri | Tauri/native runtime dependency | No | MIT |
| tendril | 0.5.1 | Transitive Rust dependency | MIT OR Apache-2.0 | Keegan McAllister, Simon Sapin, Chris Morgan | https://github.com/servo/html5ever | Tauri/native runtime dependency | No | MIT |
| thiserror | 1.0.69 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/thiserror | Tauri/native runtime dependency | No | MIT |
| thiserror | 2.0.19 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/thiserror | Tauri/native runtime dependency | No | MIT |
| time | 0.3.54 | Transitive Rust dependency | MIT OR Apache-2.0 | Jacob Pratt, Time contributors | https://github.com/time-rs/time | Tauri/native runtime dependency | No | MIT |
| time-core | 0.1.9 | Transitive Rust dependency | MIT OR Apache-2.0 | Jacob Pratt, Time contributors | https://github.com/time-rs/time | Tauri/native runtime dependency | No | MIT |
| tinystr | 0.8.3 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| tinyvec | 1.12.0 | Transitive Rust dependency | Zlib OR Apache-2.0 OR MIT | Lokathor | https://github.com/Lokathor/tinyvec | Tauri/native runtime dependency | No | MIT |
| tinyvec_macros | 0.1.1 | Transitive Rust dependency | MIT OR Apache-2.0 OR Zlib | Soveu | https://github.com/Soveu/tinyvec_macros | Tauri/native runtime dependency | No | MIT |
| tokio | 1.53.1 | Transitive Rust dependency | MIT | Tokio Contributors | https://github.com/tokio-rs/tokio | Tauri/native runtime dependency | No | MIT |
| toml | 1.1.3+spec-1.1.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/toml-rs/toml | Tauri/native runtime dependency | No | MIT |
| toml_datetime | 1.1.1+spec-1.1.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/toml-rs/toml | Tauri/native runtime dependency | No | MIT |
| toml_parser | 1.1.2+spec-1.1.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/toml-rs/toml | Tauri/native runtime dependency | No | MIT |
| toml_writer | 1.1.2+spec-1.1.0 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/toml-rs/toml | Tauri/native runtime dependency | No | MIT |
| tray-icon | 0.24.1 | Transitive Rust dependency | MIT OR Apache-2.0 | Not specified in crate metadata; package license text retained | https://github.com/tauri-apps/tray-icon | Tauri/native runtime dependency | No | MIT |
| typeid | 1.0.3 | Transitive Rust dependency | MIT OR Apache-2.0 | David Tolnay | https://github.com/dtolnay/typeid | Tauri/native runtime dependency | No | MIT |
| unic-char-property | 0.9.0 | Transitive Rust dependency | MIT/Apache-2.0 | The UNIC Project Developers | https://github.com/open-i18n/rust-unic/ | Tauri/native runtime dependency | No | MIT |
| unic-char-range | 0.9.0 | Transitive Rust dependency | MIT/Apache-2.0 | The UNIC Project Developers | https://github.com/open-i18n/rust-unic/ | Tauri/native runtime dependency | No | MIT |
| unic-common | 0.9.0 | Transitive Rust dependency | MIT/Apache-2.0 | The UNIC Project Developers | https://github.com/open-i18n/rust-unic/ | Tauri/native runtime dependency | No | MIT |
| unic-ucd-ident | 0.9.0 | Transitive Rust dependency | MIT/Apache-2.0 | The UNIC Project Developers | https://github.com/open-i18n/rust-unic/ | Tauri/native runtime dependency | No | MIT |
| unic-ucd-version | 0.9.0 | Transitive Rust dependency | MIT/Apache-2.0 | The UNIC Project Developers | https://github.com/open-i18n/rust-unic/ | Tauri/native runtime dependency | No | MIT |
| unicode-ident | 1.0.24 | Transitive Rust dependency | (MIT OR Apache-2.0) AND Unicode-3.0 | David Tolnay | https://github.com/dtolnay/unicode-ident | Tauri/native runtime dependency | No | MIT + Unicode-3.0 |
| unicode-segmentation | 1.13.3 | Transitive Rust dependency | MIT OR Apache-2.0 | kwantam, Manish Goregaokar | https://github.com/unicode-rs/unicode-segmentation | Tauri/native runtime dependency | No | MIT |
| url | 2.5.8 | Transitive Rust dependency | MIT OR Apache-2.0 | The rust-url developers | https://github.com/servo/rust-url | Tauri/native runtime dependency | No | MIT |
| urlpattern | 0.3.0 | Transitive Rust dependency | MIT | the Deno authors, crowlKats | https://github.com/denoland/rust-urlpattern | Tauri/native runtime dependency | No | MIT |
| utf8_iter | 1.0.4 | Transitive Rust dependency | Apache-2.0 OR MIT | Henri Sivonen | https://github.com/hsivonen/utf8_iter | Tauri/native runtime dependency | No | MIT |
| uuid | 1.24.0 | Transitive Rust dependency | Apache-2.0 OR MIT | Ashley Mannix, Dylan DPC, Hunar Roop Kahlon | https://github.com/uuid-rs/uuid | Tauri/native runtime dependency | No | MIT |
| walkdir | 2.5.0 | Transitive Rust dependency | Unlicense/MIT | Andrew Gallant | https://github.com/BurntSushi/walkdir | Tauri/native runtime dependency | No | MIT |
| web_atoms | 0.2.5 | Transitive Rust dependency | MIT OR Apache-2.0 | The html5ever Project Developers | https://github.com/servo/html5ever | Tauri/native runtime dependency | No | MIT |
| window-vibrancy | 0.6.0 | Transitive Rust dependency | Apache-2.0 OR MIT | Tauri Programme within The Commons Conservancy | https://github.com/tauri-apps/tauri-plugin-vibrancy | Tauri/native runtime dependency | No | MIT |
| winnow | 1.0.4 | Transitive Rust dependency | MIT | Not specified in crate metadata; package license text retained | https://github.com/winnow-rs/winnow | Tauri/native runtime dependency | No | MIT |
| writeable | 0.6.3 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| wry | 0.55.1 | Transitive Rust dependency | Apache-2.0 OR MIT | Tauri Programme within The Commons Conservancy | https://github.com/tauri-apps/wry | Tauri/native runtime dependency | No | MIT |
| yoke | 0.8.3 | Transitive Rust dependency | Unicode-3.0 | Manish Goregaokar | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| zerofrom | 0.1.8 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| zerotrie | 0.2.4 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| zerovec | 0.11.6 | Transitive Rust dependency | Unicode-3.0 | The ICU4X Project Developers | https://github.com/unicode-org/icu4x | Tauri/native runtime dependency | No | Unicode-3.0 |
| zmij | 1.0.23 | Transitive Rust dependency | MIT | David Tolnay | https://github.com/dtolnay/zmij | Tauri/native runtime dependency | No | MIT |

## Deliberately excluded development-only packages

Vite, TypeScript, Vitest, ESLint, Prettier, the Tauri CLI, type declarations, and their dependency trees are build/test tooling and are not copied into the released app bundle. `@tauri-apps/plugin-opener` is declared in the private workspace but is not imported by the production WebView and has no corresponding Rust plugin registration, so it is not bundled or listed as a distributed runtime component.

## Complete license texts

The following complete, unmodified license texts are included in this notice and as individual files directly in `Contents/Resources/licenses/` inside the app bundle.

### Apache-2.0

```text
                              Apache License
                        Version 2.0, January 2004
                     https://www.apache.org/licenses/LICENSE-2.0

TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

1. Definitions.

   "License" shall mean the terms and conditions for use, reproduction,
   and distribution as defined by Sections 1 through 9 of this document.

   "Licensor" shall mean the copyright owner or entity authorized by
   the copyright owner that is granting the License.

   "Legal Entity" shall mean the union of the acting entity and all
   other entities that control, are controlled by, or are under common
   control with that entity. For the purposes of this definition,
   "control" means (i) the power, direct or indirect, to cause the
   direction or management of such entity, whether by contract or
   otherwise, or (ii) ownership of fifty percent (50%) or more of the
   outstanding shares, or (iii) beneficial ownership of such entity.

   "You" (or "Your") shall mean an individual or Legal Entity
   exercising permissions granted by this License.

   "Source" form shall mean the preferred form for making modifications,
   including but not limited to software source code, documentation
   source, and configuration files.

   "Object" form shall mean any form resulting from mechanical
   transformation or translation of a Source form, including but
   not limited to compiled object code, generated documentation,
   and conversions to other media types.

   "Work" shall mean the work of authorship, whether in Source or
   Object form, made available under the License, as indicated by a
   copyright notice that is included in or attached to the work
   (an example is provided in the Appendix below).

   "Derivative Works" shall mean any work, whether in Source or Object
   form, that is based on (or derived from) the Work and for which the
   editorial revisions, annotations, elaborations, or other modifications
   represent, as a whole, an original work of authorship. For the purposes
   of this License, Derivative Works shall not include works that remain
   separable from, or merely link (or bind by name) to the interfaces of,
   the Work and Derivative Works thereof.

   "Contribution" shall mean any work of authorship, including
   the original version of the Work and any modifications or additions
   to that Work or Derivative Works thereof, that is intentionally
   submitted to Licensor for inclusion in the Work by the copyright owner
   or by an individual or Legal Entity authorized to submit on behalf of
   the copyright owner. For the purposes of this definition, "submitted"
   means any form of electronic, verbal, or written communication sent
   to the Licensor or its representatives, including but not limited to
   communication on electronic mailing lists, source code control systems,
   and issue tracking systems that are managed by, or on behalf of, the
   Licensor for the purpose of discussing and improving the Work, but
   excluding communication that is conspicuously marked or otherwise
   designated in writing by the copyright owner as "Not a Contribution."

   "Contributor" shall mean Licensor and any individual or Legal Entity
   on behalf of whom a Contribution has been received by Licensor and
   subsequently incorporated within the Work.

2. Grant of Copyright License. Subject to the terms and conditions of
   this License, each Contributor hereby grants to You a perpetual,
   worldwide, non-exclusive, no-charge, royalty-free, irrevocable
   copyright license to reproduce, prepare Derivative Works of,
   publicly display, publicly perform, sublicense, and distribute the
   Work and such Derivative Works in Source or Object form.

3. Grant of Patent License. Subject to the terms and conditions of
   this License, each Contributor hereby grants to You a perpetual,
   worldwide, non-exclusive, no-charge, royalty-free, irrevocable
   (except as stated in this section) patent license to make, have made,
   use, offer to sell, sell, import, and otherwise transfer the Work,
   where such license applies only to those patent claims licensable
   by such Contributor that are necessarily infringed by their
   Contribution(s) alone or by combination of their Contribution(s)
   with the Work to which such Contribution(s) was submitted. If You
   institute patent litigation against any entity (including a
   cross-claim or counterclaim in a lawsuit) alleging that the Work
   or a Contribution incorporated within the Work constitutes direct
   or contributory patent infringement, then any patent licenses
   granted to You under this License for that Work shall terminate
   as of the date such litigation is filed.

4. Redistribution. You may reproduce and distribute copies of the
   Work or Derivative Works thereof in any medium, with or without
   modifications, and in Source or Object form, provided that You
   meet the following conditions:

   (a) You must give any other recipients of the Work or
       Derivative Works a copy of this License; and

   (b) You must cause any modified files to carry prominent notices
       stating that You changed the files; and

   (c) You must retain, in the Source form of any Derivative Works
       that You distribute, all copyright, patent, trademark, and
       attribution notices from the Source form of the Work,
       excluding those notices that do not pertain to any part of
       the Derivative Works; and

   (d) If the Work includes a "NOTICE" text file as part of its
       distribution, then any Derivative Works that You distribute must
       include a readable copy of the attribution notices contained
       within such NOTICE file, excluding those notices that do not
       pertain to any part of the Derivative Works, in at least one
       of the following places: within a NOTICE text file distributed
       as part of the Derivative Works; within the Source form or
       documentation, if provided along with the Derivative Works; or,
       within a display generated by the Derivative Works, if and
       wherever such third-party notices normally appear. The contents
       of the NOTICE file are for informational purposes only and
       do not modify the License. You may add Your own attribution
       notices within Derivative Works that You distribute, alongside
       or as an addendum to the NOTICE text from the Work, provided
       that such additional attribution notices cannot be construed
       as modifying the License.

   You may add Your own copyright statement to Your modifications and
   may provide additional or different license terms and conditions
   for use, reproduction, or distribution of Your modifications, or
   for any such Derivative Works as a whole, provided Your use,
   reproduction, and distribution of the Work otherwise complies with
   the conditions stated in this License.

5. Submission of Contributions. Unless You explicitly state otherwise,
   any Contribution intentionally submitted for inclusion in the Work
   by You to the Licensor shall be under the terms and conditions of
   this License, without any additional terms or conditions.
   Notwithstanding the above, nothing herein shall supersede or modify
   the terms of any separate license agreement you may have executed
   with Licensor regarding such Contributions.

6. Trademarks. This License does not grant permission to use the trade
   names, trademarks, service marks, or product names of the Licensor,
   except as required for reasonable and customary use in describing the
   origin of the Work and reproducing the content of the NOTICE file.

7. Disclaimer of Warranty. Unless required by applicable law or
   agreed to in writing, Licensor provides the Work (and each
   Contributor provides its Contributions) on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
   implied, including, without limitation, any warranties or conditions
   of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
   PARTICULAR PURPOSE. You are solely responsible for determining the
   appropriateness of using or redistributing the Work and assume any
   risks associated with Your exercise of permissions under this License.

8. Limitation of Liability. In no event and under no legal theory,
   whether in tort (including negligence), contract, or otherwise,
   unless required by applicable law (such as deliberate and grossly
   negligent acts) or agreed to in writing, shall any Contributor be
   liable to You for damages, including any direct, indirect, special,
   incidental, or consequential damages of any character arising as a
   result of this License or out of the use or inability to use the
   Work (including but not limited to damages for loss of goodwill,
   work stoppage, computer failure or malfunction, or any and all
   other commercial damages or losses), even if such Contributor
   has been advised of the possibility of such damages.

9. Accepting Warranty or Additional Liability. While redistributing
   the Work or Derivative Works thereof, You may choose to offer,
   and charge a fee for, acceptance of support, warranty, indemnity,
   or other liability obligations and/or rights consistent with this
   License. However, in accepting such obligations, You may act only
   on Your own behalf and on Your sole responsibility, not on behalf
   of any other Contributor, and only if You agree to indemnify,
   defend, and hold each Contributor harmless for any liability
   incurred by, or claims asserted against, such Contributor by reason
   of your accepting any such warranty or additional liability.

END OF TERMS AND CONDITIONS

APPENDIX: How to apply the Apache License to your work.

   To apply the Apache License to your work, attach the following
   boilerplate notice, with the fields enclosed by brackets "[]"
   replaced with your own identifying information. (Don't include
   the brackets!)  The text should be enclosed in the appropriate
   comment syntax for the file format. We also recommend that a
   file or class name and description of purpose be included on the
   same "printed page" as the copyright notice for easier
   identification within third-party archives.

Copyright [yyyy] [name of copyright owner]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

	https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

### BSD-3-Clause

```text
Copyright (c) 2016 Dropbox, Inc.
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

### MIT

```text
The MIT License (MIT)

Copyright (c) 2015 Andrew Gallant

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

### MPL-2.0

```text
Mozilla Public License Version 2.0
==================================

1. Definitions
--------------

1.1. "Contributor"
    means each individual or legal entity that creates, contributes to
    the creation of, or owns Covered Software.

1.2. "Contributor Version"
    means the combination of the Contributions of others (if any) used
    by a Contributor and that particular Contributor's Contribution.

1.3. "Contribution"
    means Covered Software of a particular Contributor.

1.4. "Covered Software"
    means Source Code Form to which the initial Contributor has attached
    the notice in Exhibit A, the Executable Form of such Source Code
    Form, and Modifications of such Source Code Form, in each case
    including portions thereof.

1.5. "Incompatible With Secondary Licenses"
    means

    (a) that the initial Contributor has attached the notice described
        in Exhibit B to the Covered Software; or

    (b) that the Covered Software was made available under the terms of
        version 1.1 or earlier of the License, but not also under the
        terms of a Secondary License.

1.6. "Executable Form"
    means any form of the work other than Source Code Form.

1.7. "Larger Work"
    means a work that combines Covered Software with other material, in 
    a separate file or files, that is not Covered Software.

1.8. "License"
    means this document.

1.9. "Licensable"
    means having the right to grant, to the maximum extent possible,
    whether at the time of the initial grant or subsequently, any and
    all of the rights conveyed by this License.

1.10. "Modifications"
    means any of the following:

    (a) any file in Source Code Form that results from an addition to,
        deletion from, or modification of the contents of Covered
        Software; or

    (b) any new file in Source Code Form that contains any Covered
        Software.

1.11. "Patent Claims" of a Contributor
    means any patent claim(s), including without limitation, method,
    process, and apparatus claims, in any patent Licensable by such
    Contributor that would be infringed, but for the grant of the
    License, by the making, using, selling, offering for sale, having
    made, import, or transfer of either its Contributions or its
    Contributor Version.

1.12. "Secondary License"
    means either the GNU General Public License, Version 2.0, the GNU
    Lesser General Public License, Version 2.1, the GNU Affero General
    Public License, Version 3.0, or any later versions of those
    licenses.

1.13. "Source Code Form"
    means the form of the work preferred for making modifications.

1.14. "You" (or "Your")
    means an individual or a legal entity exercising rights under this
    License. For legal entities, "You" includes any entity that
    controls, is controlled by, or is under common control with You. For
    purposes of this definition, "control" means (a) the power, direct
    or indirect, to cause the direction or management of such entity,
    whether by contract or otherwise, or (b) ownership of more than
    fifty percent (50%) of the outstanding shares or beneficial
    ownership of such entity.

2. License Grants and Conditions
--------------------------------

2.1. Grants

Each Contributor hereby grants You a world-wide, royalty-free,
non-exclusive license:

(a) under intellectual property rights (other than patent or trademark)
    Licensable by such Contributor to use, reproduce, make available,
    modify, display, perform, distribute, and otherwise exploit its
    Contributions, either on an unmodified basis, with Modifications, or
    as part of a Larger Work; and

(b) under Patent Claims of such Contributor to make, use, sell, offer
    for sale, have made, import, and otherwise transfer either its
    Contributions or its Contributor Version.

2.2. Effective Date

The licenses granted in Section 2.1 with respect to any Contribution
become effective for each Contribution on the date the Contributor first
distributes such Contribution.

2.3. Limitations on Grant Scope

The licenses granted in this Section 2 are the only rights granted under
this License. No additional rights or licenses will be implied from the
distribution or licensing of Covered Software under this License.
Notwithstanding Section 2.1(b) above, no patent license is granted by a
Contributor:

(a) for any code that a Contributor has removed from Covered Software;
    or

(b) for infringements caused by: (i) Your and any other third party's
    modifications of Covered Software, or (ii) the combination of its
    Contributions with other software (except as part of its Contributor
    Version); or

(c) under Patent Claims infringed by Covered Software in the absence of
    its Contributions.

This License does not grant any rights in the trademarks, service marks,
or logos of any Contributor (except as may be necessary to comply with
the notice requirements in Section 3.4).

2.4. Subsequent Licenses

No Contributor makes additional grants as a result of Your choice to
distribute the Covered Software under a subsequent version of this
License (see Section 10.2) or under the terms of a Secondary License (if
permitted under the terms of Section 3.3).

2.5. Representation

Each Contributor represents that the Contributor believes its
Contributions are its original creation(s) or it has sufficient rights
to grant the rights to its Contributions conveyed by this License.

2.6. Fair Use

This License is not intended to limit any rights You have under
applicable copyright doctrines of fair use, fair dealing, or other
equivalents.

2.7. Conditions

Sections 3.1, 3.2, 3.3, and 3.4 are conditions of the licenses granted
in Section 2.1.

3. Responsibilities
-------------------

3.1. Distribution of Source Form

All distribution of Covered Software in Source Code Form, including any
Modifications that You create or to which You contribute, must be under
the terms of this License. You must inform recipients that the Source
Code Form of the Covered Software is governed by the terms of this
License, and how they can obtain a copy of this License. You may not
attempt to alter or restrict the recipients' rights in the Source Code
Form.

3.2. Distribution of Executable Form

If You distribute Covered Software in Executable Form then:

(a) such Covered Software must also be made available in Source Code
    Form, as described in Section 3.1, and You must inform recipients of
    the Executable Form how they can obtain a copy of such Source Code
    Form by reasonable means in a timely manner, at a charge no more
    than the cost of distribution to the recipient; and

(b) You may distribute such Executable Form under the terms of this
    License, or sublicense it under different terms, provided that the
    license for the Executable Form does not attempt to limit or alter
    the recipients' rights in the Source Code Form under this License.

3.3. Distribution of a Larger Work

You may create and distribute a Larger Work under terms of Your choice,
provided that You also comply with the requirements of this License for
the Covered Software. If the Larger Work is a combination of Covered
Software with a work governed by one or more Secondary Licenses, and the
Covered Software is not Incompatible With Secondary Licenses, this
License permits You to additionally distribute such Covered Software
under the terms of such Secondary License(s), so that the recipient of
the Larger Work may, at their option, further distribute the Covered
Software under the terms of either this License or such Secondary
License(s).

3.4. Notices

You may not remove or alter the substance of any license notices
(including copyright notices, patent notices, disclaimers of warranty,
or limitations of liability) contained within the Source Code Form of
the Covered Software, except that You may alter any license notices to
the extent required to remedy known factual inaccuracies.

3.5. Application of Additional Terms

You may choose to offer, and to charge a fee for, warranty, support,
indemnity or liability obligations to one or more recipients of Covered
Software. However, You may do so only on Your own behalf, and not on
behalf of any Contributor. You must make it absolutely clear that any
such warranty, support, indemnity, or liability obligation is offered by
You alone, and You hereby agree to indemnify every Contributor for any
liability incurred by such Contributor as a result of warranty, support,
indemnity or liability terms You offer. You may include additional
disclaimers of warranty and limitations of liability specific to any
jurisdiction.

4. Inability to Comply Due to Statute or Regulation
---------------------------------------------------

If it is impossible for You to comply with any of the terms of this
License with respect to some or all of the Covered Software due to
statute, judicial order, or regulation then You must: (a) comply with
the terms of this License to the maximum extent possible; and (b)
describe the limitations and the code they affect. Such description must
be placed in a text file included with all distributions of the Covered
Software under this License. Except to the extent prohibited by statute
or regulation, such description must be sufficiently detailed for a
recipient of ordinary skill to be able to understand it.

5. Termination
--------------

5.1. The rights granted under this License will terminate automatically
if You fail to comply with any of its terms. However, if You become
compliant, then the rights granted under this License from a particular
Contributor are reinstated (a) provisionally, unless and until such
Contributor explicitly and finally terminates Your grants, and (b) on an
ongoing basis, if such Contributor fails to notify You of the
non-compliance by some reasonable means prior to 60 days after You have
come back into compliance. Moreover, Your grants from a particular
Contributor are reinstated on an ongoing basis if such Contributor
notifies You of the non-compliance by some reasonable means, this is the
first time You have received notice of non-compliance with this License
from such Contributor, and You become compliant prior to 30 days after
Your receipt of the notice.

5.2. If You initiate litigation against any entity by asserting a patent
infringement claim (excluding declaratory judgment actions,
counter-claims, and cross-claims) alleging that a Contributor Version
directly or indirectly infringes any patent, then the rights granted to
You by any and all Contributors for the Covered Software under Section
2.1 of this License shall terminate.

5.3. In the event of termination under Sections 5.1 or 5.2 above, all
end user license agreements (excluding distributors and resellers) which
have been validly granted by You or Your distributors under this License
prior to termination shall survive termination.

************************************************************************
*                                                                      *
*  6. Disclaimer of Warranty                                           *
*  -------------------------                                           *
*                                                                      *
*  Covered Software is provided under this License on an "as is"       *
*  basis, without warranty of any kind, either expressed, implied, or  *
*  statutory, including, without limitation, warranties that the       *
*  Covered Software is free of defects, merchantable, fit for a        *
*  particular purpose or non-infringing. The entire risk as to the     *
*  quality and performance of the Covered Software is with You.        *
*  Should any Covered Software prove defective in any respect, You     *
*  (not any Contributor) assume the cost of any necessary servicing,   *
*  repair, or correction. This disclaimer of warranty constitutes an   *
*  essential part of this License. No use of any Covered Software is   *
*  authorized under this License except under this disclaimer.         *
*                                                                      *
************************************************************************

************************************************************************
*                                                                      *
*  7. Limitation of Liability                                          *
*  --------------------------                                          *
*                                                                      *
*  Under no circumstances and under no legal theory, whether tort      *
*  (including negligence), contract, or otherwise, shall any           *
*  Contributor, or anyone who distributes Covered Software as          *
*  permitted above, be liable to You for any direct, indirect,         *
*  special, incidental, or consequential damages of any character      *
*  including, without limitation, damages for lost profits, loss of    *
*  goodwill, work stoppage, computer failure or malfunction, or any    *
*  and all other commercial damages or losses, even if such party      *
*  shall have been informed of the possibility of such damages. This   *
*  limitation of liability shall not apply to liability for death or   *
*  personal injury resulting from such party's negligence to the       *
*  extent applicable law prohibits such limitation. Some               *
*  jurisdictions do not allow the exclusion or limitation of           *
*  incidental or consequential damages, so this exclusion and          *
*  limitation may not apply to You.                                    *
*                                                                      *
************************************************************************

8. Litigation
-------------

Any litigation relating to this License may be brought only in the
courts of a jurisdiction where the defendant maintains its principal
place of business and such litigation shall be governed by laws of that
jurisdiction, without reference to its conflict-of-law provisions.
Nothing in this Section shall prevent a party's ability to bring
cross-claims or counter-claims.

9. Miscellaneous
----------------

This License represents the complete agreement concerning the subject
matter hereof. If any provision of this License is held to be
unenforceable, such provision shall be reformed only to the extent
necessary to make it enforceable. Any law or regulation which provides
that the language of a contract shall be construed against the drafter
shall not be used to construe this License against a Contributor.

10. Versions of the License
---------------------------

10.1. New Versions

Mozilla Foundation is the license steward. Except as provided in Section
10.3, no one other than the license steward has the right to modify or
publish new versions of this License. Each version will be given a
distinguishing version number.

10.2. Effect of New Versions

You may distribute the Covered Software under the terms of the version
of the License under which You originally received the Covered Software,
or under the terms of any subsequent version published by the license
steward.

10.3. Modified Versions

If you create software not governed by this License, and you want to
create a new license for such software, you may create and use a
modified version of this License if you rename the license and remove
any references to the name of the license steward (except to note that
such modified license differs from this License).

10.4. Distributing Source Code Form that is Incompatible With Secondary
Licenses

If You choose to distribute Source Code Form that is Incompatible With
Secondary Licenses under the terms of this version of the License, the
notice described in Exhibit B of this License must be attached.

Exhibit A - Source Code Form License Notice
-------------------------------------------

  This Source Code Form is subject to the terms of the Mozilla Public
  License, v. 2.0. If a copy of the MPL was not distributed with this
  file, You can obtain one at http://mozilla.org/MPL/2.0/.

If it is not possible or desirable to put the notice in a particular
file, then You may include the notice in a location (such as a LICENSE
file in a relevant directory) where a recipient would be likely to look
for such a notice.

You may add additional accurate notices of copyright ownership.

Exhibit B - "Incompatible With Secondary Licenses" Notice
---------------------------------------------------------

  This Source Code Form is "Incompatible With Secondary Licenses", as
  defined by the Mozilla Public License, v. 2.0.
```

### Unicode-3.0

```text
UNICODE LICENSE V3

COPYRIGHT AND PERMISSION NOTICE

Copyright © 2020-2024 Unicode, Inc.

NOTICE TO USER: Carefully read the following legal agreement. BY
DOWNLOADING, INSTALLING, COPYING OR OTHERWISE USING DATA FILES, AND/OR
SOFTWARE, YOU UNEQUIVOCALLY ACCEPT, AND AGREE TO BE BOUND BY, ALL OF THE
TERMS AND CONDITIONS OF THIS AGREEMENT. IF YOU DO NOT AGREE, DO NOT
DOWNLOAD, INSTALL, COPY, DISTRIBUTE OR USE THE DATA FILES OR SOFTWARE.

Permission is hereby granted, free of charge, to any person obtaining a
copy of data files and any associated documentation (the "Data Files") or
software and any associated documentation (the "Software") to deal in the
Data Files or Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, and/or sell
copies of the Data Files or Software, and to permit persons to whom the
Data Files or Software are furnished to do so, provided that either (a)
this copyright and permission notice appear with all copies of the Data
Files or Software, or (b) this copyright and permission notice appear in
associated Documentation.

THE DATA FILES AND SOFTWARE ARE PROVIDED "AS IS", WITHOUT WARRANTY OF ANY
KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF
THIRD PARTY RIGHTS.

IN NO EVENT SHALL THE COPYRIGHT HOLDER OR HOLDERS INCLUDED IN THIS NOTICE
BE LIABLE FOR ANY CLAIM, OR ANY SPECIAL INDIRECT OR CONSEQUENTIAL DAMAGES,
OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS,
WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION,
ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THE DATA
FILES OR SOFTWARE.

Except as contained in this notice, the name of a copyright holder shall
not be used in advertising or otherwise to promote the sale, use or other
dealings in these Data Files or Software without prior written
authorization of the copyright holder.

SPDX-License-Identifier: Unicode-3.0

—

Portions of ICU4X may have been adapted from ICU4C and/or ICU4J.
ICU 1.8.1 to ICU 57.1 © 1995-2016 International Business Machines Corporation and others.
```

### Zlib

```text
Copyright (c) 2024 Orson Peters

This software is provided 'as-is', without any express or implied warranty. In
no event will the authors be held liable for any damages arising from the use of
this software.

Permission is granted to anyone to use this software for any purpose, including
commercial applications, and to alter it and redistribute it freely, subject to
the following restrictions:

1. The origin of this software must not be misrepresented; you must not claim
    that you wrote the original software. If you use this software in a product,
    an acknowledgment in the product documentation would be appreciated but is
    not required.

2. Altered source versions must be plainly marked as such, and must not be
    misrepresented as being the original software.

3. This notice may not be removed or altered from any source distribution.
```
