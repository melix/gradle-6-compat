## Backport plugin for Gradle 7

This plugin restores some features of Gradle 6 into Gradle 7.
It is provided as a convenience, without any guarantee.

Use it at your own risk!

Plugin authors **MUST NOT** apply this plugin to their own plugins: instead they **MUST fix the plugin**.
In other words, this plugin should only be applied on user build scripts.

### Restored behavior

* the `compile` and `runtime` configurations (as well as `testCompile` and `testRuntime`)

