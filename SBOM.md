# Source SBOM

**Initial source snapshot, not a release report.** Source commit `20434380ef67fc84255225807e340bfd1e34827c` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/rattlegram `20434380ef67fc84255225807e340bfd1e34827c`

- sbom:role: source-root
- sbom:git-commit: 20434380ef67fc84255225807e340bfd1e34827c
- sbom:git-tree: 166420f8e7df4aca25e69c4797b3c5c5c80ccf72
- sbom:source-repository: https://github.com/wave-owl/rattlegram
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "LICENSE", "sha256": "7c3c1e4d95d4c718f6e126c739c767c87866188131333f49500e48ae1abb6ab3"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/rattlegram | 20434380ef67fc84255225807e340bfd1e34827c | source-root | unresolved; manual review required |
| Conditional source requirements declared by Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by app/build.gradle | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by app/proguard-rules.pro | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by app/src/main/cpp/CMakeLists.txt | unresolved | conditional-build-runtime-requirement | unresolved |
| Conditional source requirements declared by build.gradle | unresolved | conditional-build-runtime-requirement | unresolved |
| Android Gradle Plugin 8.0.1 | unresolved | conditional-build-runtime-requirement | unresolved |
| androidx.appcompat:appcompat:1.6.1 | unresolved | conditional-build-runtime-requirement | unresolved |
| com.google.android.material:material:1.9.0 | unresolved | conditional-build-runtime-requirement | unresolved |
| androidx.constraintlayout:constraintlayout:2.1.4 | unresolved | conditional-build-runtime-requirement | unresolved |
| Android NDK/CMake 3.18.1 | unresolved | conditional-build-runtime-requirement | unresolved |
| gradle-wrapper | UNKNOWN | Syft source/package discovery | unresolved |
| /Users/gerolfziegenhain/src/wave-owl/local/sbom-upstream-results/rattlegram/.source-input/gradle/wrapper/gradle-wrapper.jar | unresolved | Syft source/package discovery | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
