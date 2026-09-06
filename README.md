# android-os-internals
## 1. Boot & System Initialization

1. **boot/**

   1. `boot-process/`
   2. `init/`
   3. `zygote/`
   4. `system-server/`

---

## 2. Android Runtime

1. **runtime/**

   1. `android-runtime/`
   2. `dalvik/`
   3. `art/`
   4. `dex/`

2. **runtime-execution/**

   1. `processes/`
   2. `threads/`
   3. `class-loading/`
   4. `garbage-collection/`
   5. `jit/`
   6. `aot/`

---

## 3. Application & Framework Architecture

1. **application-framework/**

   1. `activities/`
   2. `services/`
   3. `content-providers/`
   4. `broadcast-receivers/`

2. **framework-services/**

   1. `activity-manager/`
   2. `package-manager/`
   3. `permission-manager/`
   4. `system-server/`

---

## 4. IPC & Binder

1. **ipc/**

   1. `binder/`
   2. `ipc/`
   3. `binder-driver/`
   4. `binder-services/`
   5. `aidl/`
   6. `parcel/`

---

## 5. Process & Memory Management

1. **process-management/**

   1. `processes/`
   2. `threads/`
   3. `process-lifecycle/`
   4. `oom-management/`

2. **memory-management/**

   1. `virtual-memory/`
   2. `heap/`
   3. `shared-memory/`
   4. `ashmem/`
   5. `memory-mapping/`
   6. `garbage-collection/`

---

## 6. Linux Kernel

1. **linux-kernel/**

   1. `process-management/`
   2. `threads/`
   3. `memory-management/`
   4. `syscalls/`
   5. `file-descriptors/`
   6. `kernel-modules/`

2. **kernel-security/**

   1. `selinux/`
   2. `capabilities/`
   3. `sandboxing/`
   4. `seccomp/`

---

## 7. Filesystem & Storage

1. **filesystem/**

   1. `file-system/`
   2. `file-permissions/`
   3. `mounts/`
   4. `storage/`
   5. `procfs/`
   6. `sysfs/`

2. **shared-memory/**

   1. `ashmem/`
   2. `memory-mapping/`
   3. `shared-memory/`

---

## 8. Native Execution

1. **native-code/**

   1. `native-libraries/`
   2. `elf/`
   3. `linker/`
   4. `dynamic-linking/`

2. **jni/**

   1. `jni-architecture/`
   2. `jni-bridge/`
   3. `java-native-interface/`
   4. `native-methods/`

---

## 9. Package & Permission Management

1. **package-management/**

   1. `package-manager/`
   2. `apk-installation/`
   3. `package-parsing/`
   4. `package-signing/`
   5. `dex-loading/`

2. **permission-management/**

   1. `permission-manager/`
   2. `permission-model/`
   3. `runtime-permissions/`
   4. `app-ops/`
   5. `uid-isolation/`

---

## 10. Deep-Dive Topics

1. **reverse-engineering/**

   1. `zygote-internals/`
   2. `system-server-internals/`
   3. `binder-internals/`
   4. `activity-manager-internals/`
   5. `package-manager-internals/`
   6. `art-internals/`
   7. `dex-internals/`
   8. `jni-internals/`
   9. `linker-internals/`

2. **research-notes/**

   1. `architecture-notes/`
   2. `source-code-walkthroughs/`
   3. `debugging-notes/`
   4. `experiments/`
   5. `case-studies/`

---
### Example
binder/
- binder-overview.md
- binder-ipc.md
- binder-driver.md
- binder-security.md
