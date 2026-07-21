# NSIS packaging assets

Binary helpers used by the Windows NSIS bootstrapper (`scwx-qt/nsis/supercell-wx.nsi`), kept out of the main application repository.

## Layout

| Path | Purpose |
| - | - |
| `plugins/x86-unicode/ShellExecAsUser.dll` | Unelevated finish-page app launch |
| `plugins/ShellExecAsUser.Readme.txt` | Upstream plugin notes / attribution |

`tools/build-windows-nsis-bootstrapper.ps1` passes `SCWX_NSIS_PLUGINDIR` pointing at `plugins/x86-unicode`.
