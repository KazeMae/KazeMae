# Xin Liu / KazeMae

Southwest University of Science and Technology (**SWUST**) ACM.

I write contest-oriented tooling: QQ/OneBot bots, a small compiler, and self-hosted infra. Day-to-day languages are **Rust**, **C++**, and **Java**.

## Public projects

Original work only — these are the repos pinned on this profile.

### [FujiangBot](https://github.com/KazeMae/FujiangBot)

Rust rewrite of **福酱**, the QQ bot used in SWUST ACM groups.

OneBot 11 with NapCat / LLOneBot adapters, SQLite storage, an admin page, and hot-loadable plugins (contest calendar, Codeforces rank, problem picker, and so on).

```bash
cp config.example.toml config.toml
cargo run -p fujiang -- run --config config.toml
```

### [ShortURL](https://github.com/KazeMae/ShortURL)

Self-hosted URL shortener in Spring Boot.

MurmurHash → Base62, an in-process Bloom filter for collision checks, Redis cache, MySQL persistence, and 302 redirects with hit counts.

```bash
./mvnw spring-boot:run -Dspring-boot.run.profiles=dev
```

### [Compilation-Principle](https://github.com/KazeMae/Compilation-Principle)

SWUST 编译原理 course compiler: lexer, recursive-descent parser, and semantic analysis for a tiny C-like language (`int` / `if` / `while` / `for` / `read` / `write`). C++20.

```bash
g++ -std=c++20 lexer.cpp parse.cpp semantic.cpp compiler.cpp main.cpp -o Tcompiler.exe
./Tcompiler.exe test.test
```

## Forks

These stay attributed to upstream. They are **not** original products.

- [cc-switch](https://github.com/KazeMae/cc-switch) — fork of [farion1231/cc-switch](https://github.com/farion1231/cc-switch)
- [FastOlympicCodingHook_sublime](https://github.com/KazeMae/FastOlympicCodingHook_sublime) — fork of [DrSwad/FastOlympicCodingHook](https://github.com/DrSwad/FastOlympicCodingHook)

## Elsewhere

- Blog (Hexo): [www.cloudfall.top](https://www.cloudfall.top) — generated site lives on this repo's `webpage` branch
