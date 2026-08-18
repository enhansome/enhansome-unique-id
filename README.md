# Awesome Unique ID with stars

A curated list of awesome Unique ID libraries and resources.

Unique identifiers are used everywhere. This list contains awesome projects you can use that generate IDs or hash them for security.

## Contents

* [Generation](#generation)
* [Hash](#hash)
* [CLI Tools](#cli-tools)
* [Research](#research)
* [Contributors](#contributors)

## Generation

### Polyglot

* [uuidv7](https://github.com/nalgeon/uuidv7) ⚠️ Archived ([RFC9562 uuidv7 reference](https://www.rfc-editor.org/rfc/rfc9562#name-uuid-version-7)) - UUID 128-bit unique identifier that is time-sortable with 1 ms precision.

### JavaScript

* [nanoid](https://github.com/ai/nanoid) ⭐ 26,935 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-10 ([npm](https://www.npmjs.com/package/nanoid)) - A tiny, secure URL-friendly unique string ID generator for JavaScript.
* [uuid](https://github.com/uuidjs/node-uuid) ⭐ 15,318 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-08 ([npm](https://www.npmjs.com/package/uuid)) - Simple, fast generation of RFC4122 UUIDS.
* [shortid](https://github.com/dylang/shortid) ⭐ 5,712 | 🐛 16 | 🌐 JavaScript | 📅 2025-01-23 ([npm](https://www.npmjs.com/package/shortid)) - \[Deprecated] Amazingly short non-sequential url-friendly unique id generator.
* [cuid2](https://github.com/paralleldrive/cuid2) ⭐ 3,388 | 🐛 9 | 🌐 JavaScript | 📅 2026-08-12 ([npm](https://www.npmjs.com/package/@paralleldrive/cuid2)) - Secure, collision-resistant ids optimized for horizontal scaling and performance. Next generation uuids.
* [uuid-readable](https://github.com/Debdut/uuid-readable) ⭐ 822 | 🐛 4 | 🌐 TypeScript | 📅 2023-01-19 ([npm](https://www.npmjs.com/package/uuid-readable)) - Generate Easy to Remember, Readable UUIDs, that are Shakespearean and Grammatically Correct Sentences.
* [hyperid](https://github.com/mcollina/hyperid) ⭐ 751 | 🐛 3 | 🌐 JavaScript | 📅 2026-07-17 ([npm](https://www.npmjs.com/package/hyperid)) - Uber-fast unique id generation, for Node.js and the browser.
* [uid](https://github.com/lukeed/uid) ⭐ 667 | 🐛 2 | 🌐 JavaScript | 📅 2024-09-27 ([npm](https://www.npmjs.com/package/uid)) - Generate unique ids of any length.
* [uniqid](https://github.com/adamhalasz/uniqid) ⭐ 610 | 🐛 26 | 🌐 JavaScript | 📅 2023-06-17 ([npm](https://www.npmjs.com/package/uniqid)) - A Unique Hexatridecimal ID generator.
* [crypto-random-string](https://github.com/sindresorhus/crypto-random-string) ⭐ 588 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-23 ([npm](https://www.npmjs.com/package/crypto-random-string)) - Generate a cryptographically strong random string.
* [ksuid](https://github.com/novemberborn/ksuid) ⭐ 261 | 🐛 1 | 🌐 JavaScript | 📅 2021-10-30 ([npm](https://www.npmjs.com/package/ksuid)) - K-Sortable Globally Unique IDs
* [flake-idgen](https://github.com/T-PWK/flake-idgen) ⭐ 251 | 🐛 4 | 🌐 JavaScript | 📅 2023-01-09 ([npm](https://www.npmjs.com/package/flake-idgen)) - Flake ID generator yields k-ordered, conflict-free ids in a distributed environment.
* [human-id](https://github.com/RienNeVaPlus/human-id) ⭐ 245 | 🐛 4 | 🌐 TypeScript | 📅 2026-06-04 ([npm](https://www.npmjs.com/package/human-id)) - Generates human-readable identifier strings by chaining common (short) words of the English language.
* [puid](https://github.com/pid/puid) ⭐ 239 | 🐛 3 | 🌐 JavaScript | 📅 2021-01-20 ([npm](https://www.npmjs.com/package/puid)) - Generate a unique ID depending on time, machine and process for use in a distributed environment.
* [uid-safe](https://github.com/crypto-utils/uid-safe) ⭐ 142 | 🐛 0 | 🌐 JavaScript | 📅 2021-02-18 ([npm](https://www.npmjs.com/package/uid-safe)) - URL and cookie safe UIDs.
* [yeast](https://github.com/unshiftio/yeast) ⭐ 45 | 🐛 2 | 🌐 JavaScript | 📅 2023-01-10 ([npm](https://www.npmjs.com/package/yeast)) - Yeast is a unique id generator.
* [uniqueid](https://github.com/jonschlinkert/uniqueid) ⭐ 18 | 🐛 0 | 🌐 JavaScript | 📅 2023-12-12 ([npm](https://www.npmjs.com/package/uniqueid)) - Generate sequential IDs, with optional prefix or suffix.
* [get-uid](https://github.com/dfcreative/get-uid) ⭐ 11 | 🐛 0 | 🌐 JavaScript | 📅 2015-01-25 ([npm](https://www.npmjs.com/package/get-uid)) - Simple random id generator.
* [breezeid](https://github.com/tzwel/BreezeID) ⭐ 8 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-13 ([npm](https://www.npmjs.com/package/breezeid)) - Easily generate unique, human-first IDs
* [unique-sequence](https://github.com/kayomarz/unique-sequence) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2022-01-15 ([npm](https://www.npmjs.com/package/unique-sequence)) - Generate short sequential strings.
* [ulid](https://github.com/ulid) ([npm](https://www.npmjs.com/package/ulid)) - Universally Unique Lexicographically Sortable Identifier.
* [Sqids](https://sqids.org) ([npm](https://www.npmjs.com/package/sqids)) - Sqids is a small JavaScript library to generate YouTube-like ids from numbers.

### Python

* [muid](https://github.com/microprediction/muid) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2022-09-29 ([PyPI](https://pypi.org/project/muid/)) - Generates IDs whose hashes are, in part, memorable.

### Go

* [ksuid](https://github.com/segmentio/ksuid) ⭐ 5,263 | 🐛 22 | 🌐 Go | 📅 2026-06-25 - K-Sortable Globally Unique IDs.
* [xid](https://github.com/rs/xid) ⭐ 4,281 | 🐛 18 | 🌐 Go | 📅 2026-07-24 - Xid is a globally unique id generator thought for the web.

## Hash

* [RoboHash](https://robohash.org/) ([GitHub](https://github.com/e1ven/Robohash) ⭐ 1,344 | 🐛 2 | 🌐 JavaScript | 📅 2026-07-21) - Generate unique images from any text.

## CLI Tools

* [uuinfo](https://github.com/racum/uuinfo) ⭐ 66 | 🐛 0 | 🌐 Rust | 📅 2026-05-31 - A tool to debug unique identifiers (UUID, ULID, Snowflake, etc).
* [OSSP uuid](http://www.ossp.org/pkg/lib/uuid/) - ISO-C API and CLI for generating UUIDs

## Research

* Articles/papers
  * [The definitive guide to modulo bias and how to avoid it](https://web.archive.org/web/20260226080934/https://research.kudelskisecurity.com/2020/07/28/the-definitive-guide-to-modulo-bias-and-how-to-avoid-it) (archive) - Generate unbiased random numbers.
  * [Efficiently generating a number in range](https://www.pcg-random.org/posts/bounded-rands.html) - Discusses performance problems in PRNGs and many algorithms.
  * [Understanding modulo bias](https://web.archive.org/web/20240802033931/https://julian.bayardo.info/understanding-modulo-bias/) (archive)
  * [Choose your database identifiers wisely](https://racum.blog/articles/identifiers/) - A comprehensive article explaining types and implementations of identifiers.

* Collision calculators
  * [Devina.io collision calculator](https://devina.io/collision-calculator)
  * [Nano ID collision calculator (by Alexey Komarov)](https://alex7kom.github.io/nano-nanoid-cc/)
  * [Nano ID collision calculator (by Aleksandr Zhuravlёv)](https://zelark.github.io/nano-id-cc/)

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<!-- prettier-ignore-start -->

<!-- markdownlint-disable -->

<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/tzwel"><img src="https://avatars.githubusercontent.com/u/39600182?v=4?s=100" width="100px;" alt="tzwel"/><br /><sub><b>tzwel</b></sub></a><br /><a href="#content-tzwel" title="Content">🖋</a> <a href="https://github.com/grantcarthew/awesome-unique-id/commits?author=tzwel" title="Documentation">📖</a> <a href="#ideas-tzwel" title="Ideas, Planning, & Feedback">🤔</a> <a href="#maintenance-tzwel" title="Maintenance">🚧</a> <a href="#research-tzwel" title="Research">🔬</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/kayomarz"><img src="https://avatars.githubusercontent.com/u/140297?v=4?s=100" width="100px;" alt="Kayomarz"/><br /><sub><b>Kayomarz</b></sub></a><br /><a href="#content-kayomarz" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://madcity.at"><img src="https://avatars.githubusercontent.com/u/343392?v=4?s=100" width="100px;" alt="Matthias Esterl"/><br /><sub><b>Matthias Esterl</b></sub></a><br /><a href="#content-madc" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://microprediction.medium.com/"><img src="https://avatars.githubusercontent.com/u/57455669?v=4?s=100" width="100px;" alt="Peter Cotton"/><br /><sub><b>Peter Cotton</b></sub></a><br /><a href="#content-microprediction" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/amitlzkpa"><img src="https://avatars.githubusercontent.com/u/15354742?v=4?s=100" width="100px;" alt="Amit Nambiar"/><br /><sub><b>Amit Nambiar</b></sub></a><br /><a href="#content-amitlzkpa" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/cuongndc"><img src="https://avatars.githubusercontent.com/u/34389409?v=4?s=100" width="100px;" alt="Cuong Nguyen"/><br /><sub><b>Cuong Nguyen</b></sub></a><br /><a href="#content-cuongndc" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.racum.com/"><img src="https://avatars.githubusercontent.com/u/236879?v=4?s=100" width="100px;" alt="Ronaldo Ferreira"/><br /><sub><b>Ronaldo Ferreira</b></sub></a><br /><a href="#content-Racum" title="Content">🖋</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->

<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
