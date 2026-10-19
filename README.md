# TB4.0 task archives

Public, immutable task ZIPs for Harbor source imports. Use the archive URL pinned to a complete Git commit, and verify its SHA-256 against the matching manifest.

The original session-window-debug archive contains the 25 unchanged source assets used for the baseline control.

## Artifact directory compatibility control

`archives/original-session-window-debug-artifact-compat.zip` adds an explicit private-verifier directory-mode bootstrap to the original control. The original instruction, application, seven tests and reference solution bytes are preserved. Only task identity and verifier environment metadata change. The corresponding manifest records every archive member hash. This derived version requires fresh native validation.
