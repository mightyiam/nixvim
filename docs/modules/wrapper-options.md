# Platform-specific options

All of Nixvim's options are available within `programs.nixvim.*` when Nixvim is used via wrapper modules,
such as our NixOS, home-manager, or nix-darwin modules.

When Nixvim is used standalone (without a wrapper module), its options are available at the "top-level".
See [Standalone Usage](./standalone.md) for more info.

There are a few wrapper specific options that are documented below:

@WRAPPER_OPTIONS@

