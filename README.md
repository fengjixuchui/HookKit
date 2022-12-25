# HookKit
An iOS tweak developer framework to unify code substitution APIs in runtime.

... I actually don't know how useful this is. (but it's quite fun to see it work)

## About
This framework allows tweak developers to hook functions with a standard and consistent API. Batch hooking is supported (if available) through the class `HKBatchHook`. To use this frameowrk, run `install_to_theos.sh` to install HookKit to your development environment, add `HookKit` to `<project_name>_EXTRA_FRAMEWORKS`, and add `me.jjolano.fmwk.hookkit` to your package dependencies.

Refer to `HookKit.h`.

## Library Support
So far, support has been (mostly) implemented for the following code substitution APIs:
* libhooker
* Substitute
* Cydia Substrate
* Fishhook
