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

I design and audit **self-contained cryptographic software** built from first principles — favoring transparent mathematics, constant-time execution, atomic filesystem safety, and zero third-party supply-chain bloat.

| Area | What I Build & Audit |
| :--- | :--- |
| **Symmetric Primitives** | Custom sponge permutations (`WilisPerm-384`), ARX + bitsliced nonlinear layers (`Chi-5` / `Feistel-6`), duplex AEAD, keyed sponge MAC, XOF, and hybrid memory-hard KDFs |
| **Post-Quantum Cryptography** | Constant-time Module-LWE IND-CCA2 KEM (Fujisaki-Okamoto implicit rejection), hybrid public-key containers (`WPKE`), and stateful hash-based `WOTS+` Merkle signatures |
| **Systems & Memory Safety** | Zero-dependency pure Rust (`std` only), volatile secret zeroization, panic-safe C99 ABI (`libwilis`), Python `ctypes` FFI, and symlink/TOCTOU-safe atomic persistence |
| **Adversarial Verification** | Locked Known-Answer Test Vectors (KAT), mutation parser fuzzing, live SAC/BIC/DDT/LAT/NIST statistical audits, and multi-OS CI (`-D warnings`, C99 `-Wall -Wextra -Werror`) |

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
| **[Repository](https://github.com/wiersect/wilis)** | Full flat-layout pure-Rust implementation (`core/`, `aead/`, `kem/`, `sign/`, `ratchet/`, `kdf/`, `split/`, `stream/`, `archive/`, `vault/`, `audit/`, `ffi/`) |
| **[Cryptographic Specification](https://github.com/wiersect/wilis/blob/main/SPECIFICATION.md)** | Complete mathematical spec & binary wire formats (`WILS` v1/v2, `WPKE`, `WKP1`/`WKS1`/`WKC1`, `WSK1`/`WPK1`/`WSIG`, `WRAT`, `WSHR`, `WDIR`, `WVLT`) |
| **[Security Policy & Audit Log](https://github.com/wiersect/wilis/blob/main/CHANGELOG.md)** | 7 consecutive full-codebase red-team audit releases (`v0.4.1`–`v0.4.7`), locked cross-architecture KAT vectors & zero-dependency enforcement |
| **[Prebuilt Binaries](https://github.com/wiersect/wilis/releases)** | Automated native builds & checksums for Linux (`x86_64`), macOS (`ARM64`), and Windows (`x86_64`) |

---

### Stack & Tooling

<div align="left">
  <img src="https://img.shields.io/badge/Rust-0f172a?style=flat-square&logo=rust&logoColor=f97316" alt="Rust" />
  <img src="https://img.shields.io/badge/C99%20ABI-0f172a?style=flat-square&logo=c&logoColor=38bdf8" alt="C99" />
  <img src="https://img.shields.io/badge/Python%203-0f172a?style=flat-square&logo=python&logoColor=facc15" alt="Python 3" />
  <img src="https://img.shields.io/badge/Linux-0f172a?style=flat-square&logo=linux&logoColor=e2e8f0" alt="Linux" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-0f172a?style=flat-square&logo=githubactions&logoColor=60a5fa" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Git-0f172a?style=flat-square&logo=git&logoColor=fb7185" alt="Git" />
</div>

---

<div align="center">
  <sub><code>Built from first principles · Zero external dependencies · Kerckhoffs's Principle</code></sub>
</div>
