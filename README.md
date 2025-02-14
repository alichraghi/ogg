# ogg packaged for the Zig build system

This is a fork of [ogg](https://github.com/xiph/ogg), packaged for Zig. Unnecessary files have been deleted, and the build system has been replaced with build.zig.

_Looking for Zig bindings to Ogg?_ See [mach-ogg](https://github.com/hexops/mach-ogg).

## Updating

To update this repository, run `./update.sh` followed by `./verify.sh` to verify the repository contents.

## Verifying repository contents

For supply chain security reasons (e.g. to confirm we made no patches to the code) we provide a `git diff` command you can run to verify the contents of this repository:

```sh
./verify.sh
```

If nothing is printed, there is no diff. Deleted files, and changes to `README.md`, `build.zig`, `.github` CI files and `.gitignore` are ignored.
