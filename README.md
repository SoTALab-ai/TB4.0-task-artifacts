# TB4.0 task archives

Public, immutable task ZIPs for Harbor source imports. Use the archive URL pinned to a complete Git commit, and verify its SHA-256 against the matching manifest.

The original session-window-debug archive contains the 25 unchanged source assets used for the baseline control.

## Artifact directory compatibility control

`archives/original-session-window-debug-artifact-compat.zip` adds an explicit private-verifier directory-mode bootstrap to the original control. The original instruction, application, seven tests and reference solution bytes are preserved. Only task identity and verifier environment metadata change. The corresponding manifest records every archive member hash. This derived version requires fresh native validation.

## Operational-history v4 native QA carrier

`archives/session-window-operational-history-v4-native-qa-21.zip` is the frozen private-case Oracle QA carrier. It retains the source seven formal tests and applies an explicitly recorded offline Agent policy for QA execution. Its reward is not a reference-solution or model-performance result. The manifest binds the archive and minimal runtime module closure.
