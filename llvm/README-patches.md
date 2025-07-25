# Patches statuses

Legend:

- :grey_exclamation: - not meant to upstream, for compatibility with GCC only
- :x: - not upstreamed
- :grey_question: - sent but not merged yet
- :arrow_up_small:  - upstreamed
- :arrow_down_small:  - backported

-----

- `"0001-LLVM-Cygwin-Fix-symbol-visibility-definition.patch"` :x:
- `"0002-LLVM-Cygwin-Remove-special-case-for-CXX-extensions-o.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/497fbd0ee0c4c50d46b5b777cdcc3a532d1dcc91
- `"0003-LLVM-Cygwin-Fix-shared-library-name-136599.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/08efca9c2c2b9005a0390965a2bad9ef208e4db4
- `"0004-LLVM-Cygwin-Fix-Signals-compatibility-with-Cygwin-AP.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/8a84a19cf9ccbc1d0878f51b0466dc3a3b93dbe3
- `"0005-LLVM-TargetParser-Handle-msys-targets-the-same-as-cy.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/6900e9026516963ae625b28dded2cdf0bd16e590
- `"0006-LLVM-Cygwin-Define-_GNU_SOURCE-on-Cygwin-as-well.-13.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/9633f87e34dddce49619e7fc2d75c659c61a9db1
- `"0007-Cygwin-Emit-COMDAT-name-correctly-for-Cygwin-138621.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/7157228667396f1c113a96e9e9ecb9f0ca82a645
- `"0008-LLVM-Cygwin-add-workaround-for-blocking-connect-acce.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/7857543a6350f49f12d17af0bcf2c0f42db0311e
- `"0009-Support-Cygwin-Fix-handling-of-Process-symbol-lookup.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/d659364295f6f0c41535a0c98c958cb4c896cc62
- `"0010-Cygwin-Define-LLVM_ABI-for-Cygwin-143222.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/60d000496b5485c89c51e64b2b339210d48263be
- `"0011-Cygwin-CYGWIN-is-not-WIN32-in-current-CMake-143130.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/bd319d9071fb0c6e1bda9db500d039d32a49c28a
- `"0012-Cygwin-Don-t-use-version-script-for-Cygwin-target-14.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/0bd614a8ee11cfc5cee8719b3209f40b163d5a62
- `"0013-LLVM-Tests-remove-exeext-from-lli-child-target-param.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/d34b392dade4f9f0ef981767a9a47504ba85d0af
- `"0014-LLVM-Support-Cygwin-Add-threading-support-for-Cygwin.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/bd96918f01cfd7642a20a4a5bb0e7d10ad7f2360
- `"0015-LLVM-Cygwin-Enable-dynamic-linking-of-libLLVM-146440.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/2723a6d9928c7ba5d27125e03dff8eaba8661d7f
- `"0101-Cygwin-Global-symbols-should-be-external-by-default-.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/76d866f7935b746e5e50e7d760344c14502bd8e7
- `"0102-Clang-Cygwin-Enable-few-conditions-that-are-shared-w.patch"` :x:
- `"0103-Cygwin-Enable-TLS-on-Cygwin-target-138618.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/eb6d51a2fdddcc305b51f7d412d0e5144cbd444d
- `"0104-Clang-Cygwin-Fix-symbol-visibility-definition-138118.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/592243c1cb3ea53b34033132a87b0d14af9d1079
- `"0105-Cygwin-RTTI-and-VTable-should-be-dllexport-ed-139798.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/a3d52ea99e1438d6cd39de2eb27e43ac27700bf7
- `"0106-Clang-Cygwin-Disable-shared-libs-on-Cygwin-by-defaul.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/9bc20fbbadb18a1c3415d4442066ed35a6bcc175
- `"0107-Clang-Cygwin-Remove-erroneous-_WIN32-define-and-clea.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/abe93fe7c88c477343c884036982ddc15f820425
- `"0108-Clang-Cygwin-don-t-use-Bsymbolic-functions-138217.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/74d921c01ab4aefb5f7f14062ab4aef50d5c6413
- `"0109-hack-cygwin-allow-multiple-definition-in-c-index-tes.patch"` :grey_exclamation:
- `"0110-Clang-Driver-add-a-Cygwin-ToolChain.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/52924a2d7255cdd280b2b82dad8616e01fe065da
- `"0111-Clang-Driver-use-__cxa_atexit-by-default-on-Cygwin.-.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/ca3a5d37ef64668234cbce7236dd640a98e2d687
- `"0112-Clang-CMake-use-CMakePushCheckState-138783.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/74c0422cfeac42c83b82a3ff5c0c0cde849bd240
- `"0113-CMake-respect-LLVMConfig.cmake-s-LLVM_DEFINITIONS.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/ba4bd3f46e97b5637b16a0fa74b064fb3e6db8ff
- `"0114-Cygwin-Internal-class-in-explicitly-instantiation-de.patch"` :grey_exclamation:
- `"0115-Cygwin-Template-instantiations-should-be-exported-by.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/cb53ece2cab0096539e6a5c9d53da4e5db5cc270
- `"0116-Cygwin-va_list-must-be-treated-like-normal-Windows.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/830a74092adafa425db05e1c5120d3294f874777
- `"0117-Cygwin-wint_t-is-unsigned-int.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/e7739eb6ccb775a2cfc2f68c3d2356ceeabdf94a
- `"0118-scan-build-Windows-Fix-driver-name-transformation-in.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/b07a6da7cbe9326d5cc64b55a7cfd582bd51b325
- `"0119-libclang-Add-missing-dllexport-annotation-147108.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/968410ffd1bacbf540595e0b6d2628ed559098e9
- `"0120-libclang-Cygwin-Use-__declspec-dllexport-for-libclan.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/122afae10ed28564b64530de571ce8e4ce584b2c
- `"0121-libclang-Cygwin-Use-LLVM_EXPORTED_SYMBOL_FILE-.def-f.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/9c4e2dcb56eeb82619762ecfe4ae69ec479de4b3
- `"0201-LLD-Cygwin-Implement-dll-search-prefix-143263.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/9e23e85d6597bd59ff316a3ce93bb8ec41919b19
- `"0202-LLD-COFF-Ensure-.bss-is-merged-at-the-end-of-a-secti.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/bb2f7596a8b963af06e9dde821dcea1252ba4892
- `"0203-LLD-COFF-add-__-data-bss-_-start-end-__-symbols-for-.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/f66f2fe0e5be6dc6eb3ef4d42af8692f9adcdc80
- `"0204-LLD-MinGW-Fall-back-to-using-default-target-if-no-m-.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/e4a79b7122cbe6470c1a42e7b3549c37a1a6408d
- `"0205-LLD-CMake-fix-testing-standalone-build-without-insta.patch"` :arrow_up_small: https://github.com/llvm/llvm-project/commit/16107c88fb6cc474e1e5691025eb295df094a6c2
- `"0206-LLD-Cygwin-Add-libcygwin-and-libmsys-2.0-to-exclude-.patch"` :arrow_down_small: https://github.com/llvm/llvm-project/commit/89aef7e0608d927eb7613834d817b723feef4f83
