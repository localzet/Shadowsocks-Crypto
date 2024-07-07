<p align="center"><a href="https://www.localzet.com" target="_blank">
  <img src="https://cdn.localzet.com/assets/media/logos/ZorinProjectsSP.svg" width="400">
</a></p>

<p align="center">
  <a href="https://github.com/localzet/shadowsocks-crypto">
    <img src="https://img.shields.io/github/commit-activity/t/localzet/shadowsocks-crypto?label=%D0%9A%D0%BE%D0%BC%D0%BC%D0%B8%D1%82%D1%8B" alt="Коммиты">
  </a>
  <a href="https://github.com/localzet/shadowsocks-crypto/releases">
    <img src="https://img.shields.io/github/downloads/localzet/shadowsocks-crypto/total.svg" alt="Релизы">
  </a>
  <a href="https://github.com/localzet/shadowsocks-crypto/search?l=rust">
    <img src="https://img.shields.io/github/languages/top/localzet/shadowsocks-crypto.svg" alt="Язык">
  </a>
  <a href="https://www.gnu.org/licenses/agpl-3.0">
    <img src="https://img.shields.io/github/license/localzet/shadowsocks-crypto?label=%D0%9B%D0%B8%D1%86%D0%B5%D0%BD%D0%B7%D0%B8%D1%8F" alt="Лицензия">
  </a>
</p>

# shadowsocks-crypto

[![Build & Test](https://github.com/localzet/shadowsocks-crypto/actions/workflows/build-and-test.yml/badge.svg)](https://github.com/localzet/shadowsocks-crypto/actions/workflows/build-and-test.yml)

shadowsocks' flavored cryptographic algorithm in pure Rust.

## Supported Ciphers

Stream Ciphers:

* [x] SS\_TABLE
* [x] SS\_RC4\_MD5
* [x] AES\_128\_CTR, AES\_192\_CTR, AES\_256\_CTR
* [x] AES\_128\_CFB1, AES\_128\_CFB8, AES\_128\_CFB128, AES\_192\_CFB1, AES\_192\_CFB8, AES\_192\_CFB128, AES\_256\_CFB1, AES\_256\_CFB8, AES\_256\_CFB128
* [x] AES\_128\_OFB, AES\_192\_OFB, AES\_256\_OFB
* [x] CAMELLIA\_128\_CTR, CAMELLIA\_192\_CTR, CAMELLIA\_256\_CTR
* [x] CAMELLIA\_128\_CFB1, CAMELLIA\_128\_CFB8, CAMELLIA\_128\_CFB128, CAMELLIA\_192\_CFB1, CAMELLIA\_192\_CFB8, CAMELLIA\_192\_CFB128, CAMELLIA\_256\_CFB1, CAMELLIA\_256\_CFB8, CAMELLIA\_256\_CFB128
* [x] CAMELLIA\_128\_OFB, CAMELLIA\_192\_OFB, CAMELLIA\_256\_OFB
* [x] RC4
* [x] CHACHA20 (IETF Version)

AEAD Ciphers：

* [x] AES\_128\_CCM, AES\_256\_CCM
* [x] AES\_128\_GCM, AES\_256\_GCM
* [x] AES\_128\_GCM\_SIV, AES\_256\_GCM\_SIV
* [x] CHACHA20\_POLY1305 (IETF Version)
* [x] XCHACHA20\_POLY1305 (IETF Version)
* [ ] AES\_128\_OCB\_TAGLEN128, AES\_192\_OCB\_TAGLEN128, AES\_256\_OCB\_TAGLEN128
* [ ] AES\_SIV\_CMAC\_256, AES\_SIV\_CMAC\_384, AES\_SIV\_CMAC\_512
* [x] SM4\_GCM, SM4\_CCM

AEAD 2022 Ciphers ([SIP022](https://github.com/shadowsocks/shadowsocks-org/issues/196)):

* [x] AEAD2022\_BLAKE3\_AES\_128\_GCM, AEAD2022\_BLAKE3\_AES\_256\_GCM
* [x] AEAD2022\_BLAKE3\_CHACHA20\_POLY1305, AEAD2022\_BLAKE3\_CHACHA8\_POLY1305
