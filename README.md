<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./assets/header-light.svg" />
    <img alt="Wies (@wiersect) — Cryptography & Systems Engineering" src="./assets/header-dark.svg" width="100%" />
  </picture>
</div>

<br />

<div align="center">
  <a href="https://github.com/wiersect/wilis/releases">
    <img src="https://img.shields.io/github/v/release/wiersect/wilis?style=flat-square&label=Wilis&color=7c3aed" alt="Wilis Release" />
  </a>
  <a href="https://github.com/wiersect/wilis/actions/workflows/ci.yml">
    <img src="https://img.shields.io/github/actions/workflow/status/wiersect/wilis/ci.yml?style=flat-square&label=Multi-OS%20CI" alt="CI Status" />
  </a>
  <a href="https://github.com/wiersect/wilis/blob/main/Cargo.toml">
    <img src="https://img.shields.io/badge/Dependencies-0%20External%20Crates-10b981?style=flat-square" alt="Zero External Dependencies" />
  </a>
  <a href="https://github.com/wiersect/wilis/blob/main/SPECIFICATION.md">
    <img src="https://img.shields.io/badge/Spec-Kerckhoffs%20Verified-0284c7?style=flat-square" alt="Open Specification" />
  </a>
</div>

---

### Focus & Engineering Principles

I work on both sides of security — **breaking assumptions through penetration testing & offensive auditing**, and **developing self-contained systems & cryptographic software** from first principles.

| Area | What I Build & Break |
| :--- | :--- |
| **Penetration Testing & Offensive Security** | Security assessments, vulnerability research, attack-surface analysis, white-box code auditing, and adversarial red-team testing |
| **Software & Systems Development** | Pure Rust (`std` only), C99 ABI (`libwilis`), Python tooling, CLI engineering, atomic crash-safe I/O, and zero supply-chain bloat |
| **Cryptography Engineering** | Custom sponge permutations (`WilisPerm-384`), duplex AEAD, post-quantum Module-LWE KEM (`IND-CCA2`), `WOTS+` Merkle signatures, forward-secret ratchets & memory-hard KDFs |
| **Adversarial Verification** | Mutation parser fuzzing, TOCTOU/FFI memory-safety hardening, locked Known-Answer Test Vectors (KAT), live SAC/BIC/DDT/LAT/NIST audits, and multi-OS CI (`-D warnings`) |

---

### Flagship Project

<div align="center">
  <a href="https://github.com/wiersect/wilis">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/wilis-card-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="./assets/wilis-card-light.svg" />
      <img alt="wiersect/wilis — Standalone Post-Quantum & Symmetric Cryptography Suite" src="./assets/wilis-card-dark.svg" width="100%" />
    </picture>
  </a>
</div>

<br />

| Quick Links | Details |
| :--- | :--- |
| **[Repository](https://github.com/wiersect/wilis)** | Full flat-layout pure-Rust implementation (`core/`, `aead/`, `kem/`, `sign/`, `ratchet/`, `net/`, `protocols/`, `kdf/`, `hash/`, `split/`, `stream/`, `archive/`, `vault/`, `audit/`, `ffi/`) |
| **[Cryptographic Specification](https://github.com/wiersect/wilis/blob/main/SPECIFICATION.md)** | Complete mathematical spec & binary wire formats (`WILS` v1/v2, `WSEK`, `WPKE` v1/v2, `WPSC`, `WLP1`/`WLSG`, `WHSH`/`WRP2`/`WPRK`/`WRST`, `WNET`, `WDIR` v1/v2, `WVLT`, `WENC`/`WKRN`) |
| **[Security Policy & Audit Log](https://github.com/wiersect/wilis/blob/main/CHANGELOG.md)** | `v0.7.0` 33-export C-ABI & **16 zero-dep language bindings**, NTT/SIMD, SIV, stateless `WilisSLH`, `WilisNet` PQ TCP, Miri UB CI, 8-part audit (`dudect`), 64/64 tests & 0 external crates |
| **[Prebuilt Binaries](https://github.com/wiersect/wilis/releases)** | Automated native builds & checksums for Linux (`x86_64`), macOS (`ARM64`), and Windows (`x86_64`) |

---

### Stack & Tooling

<div align="left">
  <img src="https://img.shields.io/badge/Rust-0f172a?style=flat-square&logo=rust&logoColor=f97316" alt="Rust" />
  <img src="https://img.shields.io/badge/C99%20ABI-0f172a?style=flat-square&logo=c&logoColor=38bdf8" alt="C99" />
  <img src="https://img.shields.io/badge/Python%203-0f172a?style=flat-square&logo=python&logoColor=facc15" alt="Python 3" />
  <img src="https://img.shields.io/badge/Bash-0f172a?style=flat-square&logo=gnubash&logoColor=4ade80" alt="Bash" />
  <img src="https://img.shields.io/badge/Linux-0f172a?style=flat-square&logo=linux&logoColor=e2e8f0" alt="Linux" />
  <img src="https://img.shields.io/badge/Pentesting-0f172a?style=flat-square&logo=kalilinux&logoColor=fb7185" alt="Pentesting" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-0f172a?style=flat-square&logo=githubactions&logoColor=60a5fa" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Git-0f172a?style=flat-square&logo=git&logoColor=fb923c" alt="Git" />
</div>

---

<div align="center">
  <sub><code>Break to understand · Build from first principles · Zero external dependencies</code></sub>
</div>
