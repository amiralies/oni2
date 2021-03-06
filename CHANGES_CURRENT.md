### Features 

- #3163 - UX: Add clear notification button (thanks @andr3h3nriqu3s11 !)

### Bug Fixes

- #3141 - Windows: Reload keybindings on save
- #3145 - Vim: Don't crash on confirm flag with substitute ex command (fixes #1159, related #2965)
- #3142 - Windows: Explorer - Directory nodes not expanding (fixes #3092, #2213)
- #3147 - Editor: Fix minimap scroll synchronization for large files
- #3077 - Terminal: Use editor font as default (related #3062)
- #3146 - Vim: Fix command-line staying open when clicking the editor or file explorer (fixes #3031)
- #3161 - Configuration: Turn soft word-wrap on by default (fixes #3161)
- #3162 - Windows: Support opening UNC paths (fixes #3151)
- #3166 - Windows: Fix dead key input (fixes #3157)
- #3167 - Diagnostics: Show full path to trace file
- #3170 - CLI - Windows: Allocate console with `-f --silent`
- #3180 - Explorer: Fix explorer disappearing when changing into current path
- #3183 - Auto-update: Default auto-update channel should match source build
- #3184 - Explorer: Fix shrinking when changing paths
- #3160 - Windows: Reload configuration on save
- #3194 - Completion: Fix enter key deleting text after closing pairs (fixes #3191)
- #3197 - Vim: Fix hang when using the `experimental.viml` setting (fixes #3196 - thanks @amiralies!)
- #3205 - Editor: Update highlights and diagnostics immediately on buffer update (fixes #2620, #1459)

### Performance

- #3148 - Large Files: Improve performance & fix crash when opening large files (related #1670)
- #3139 - Large Files: Fix hang when using `/` search (fixes #1670)

### Documentation

- #3181 - Snippets: Initial snippets section
- #3185 - Emmet: Initial emmet section

### Infrastructure / Refactoring

- #3156 - Dependency: reason-native (dir/fp/fs) -> e16590c
- #3164, #3171, #3177, #3179, #3188 - Configuration: Move legacy configuration parsers to new model
- #3169 - Extensions: Remove some unused static assets from One Dark Pro
- #3168 - Diagnostics: Add additional build-information logging
- #3172 - Theme: Move theme loader to subscription (unblocks #3160)
- #3178 - Commands: Remove unused contributedCommands argument
- #3202 - Dependency: revery -> 2a59280
