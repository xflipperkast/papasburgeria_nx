# License notices and distribution status

This file grants no new rights and does not relicense inherited code. The
standalone source and binary are local distribution candidates. An overall
license grant for the inherited compatibility implementation and complete
preferred source/provenance for its legacy Java boot DEX remain unresolved.
Those are inherited limitations, not claims that this project is cleared for
publication. Build independence does not resolve licensing obligations.

Retain original source copyright headers and the included notices:

| Component | Notice / terms |
|---|---|
| Android framework resources and API declarations | AOSP Apache-2.0; `assets/system/licenses/ANDROID_FRAMEWORK_SDK_NOTICE.txt` |
| Android/OpenJDK Java boot code | Mixed Android/Harmony/OpenJDK terms, including GPLv2 with Classpath Exception for designated files; `licenses/AOSP_LIBCORE_LICENSE`, `AOSP_LIBCORE_NOTICE`, `OPENJDK_NOTICE` |
| Unicode tables | `assets/system/licenses/UNICODE.txt`, `licenses/UNICODE_FRAMEWORK.txt` |
| System fonts | `assets/system/fonts/NOTICE`, accompanying README and manifest |
| SQLite | Public-domain dedication in `third_party/sqlite/sqlite3.c` |
| minimp3 | Public-domain/CC0 dedication in `third_party/minimp3/minimp3.h` |
| Mesa | Pinned source and local generic EGL patch in `tools/mesa`; `licenses/MESA_LICENSE.html` |
| curl | Pinned source/build in `tools/libcurl`; `licenses/CURL_COPYING` |
| Mbed TLS | `licenses/MBEDTLS_LICENSE`; verify against the linked installed version |
| FreeType, libogg/libvorbis, zlib, libdrm_nouveau | Preserve the notices for the recorded devkitPro versions |
| libnx and compiler runtimes | Retain applicable notices, corresponding source and runtime exceptions |

Full API30 declarations, resource tables and system fonts are provided unchanged
as source inputs under `assets/system`, together with unchanged Java boot DEX
images. The build embeds these in the complete runtime's RomFS and compresses
that runtime inside the installable NRO. It does not require the private parent
repository. Correspondence to
the complete original preferred Java sources still needs review before release.

The user-provided game's APK, libraries, assets and trademarks belong to their
rightsholders and are excluded from both distributable ZIPs. The hbmenu artwork
in `icon.jpg` and the NRO comes from the supplied APK's
`res/mipmap-xxxhdpi/ic_launcher.png`; no artwork redistribution license was
provided. Its inclusion follows the requested local port packaging; publication
rights need review. The author metadata `xFlippy` identifies the port maintainer.

There are no game-native patches, entitlement modifications or automatically
selected consent actions. The APK is read unchanged. Resolve the outstanding
license grants, corresponding-source obligations and artwork rights before
publishing these candidates.
