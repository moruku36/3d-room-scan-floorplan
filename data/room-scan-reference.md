# Original room scan reference

## Source

- Polycam capture: https://poly.cam/capture/A563F82A-8B22-46D5-BE74-9D4EBC7DAFCD
- Export format used in the validation: GLB / glTF binary
- Local source filename used during analysis: `9_13_2026.glb`
- SHA-256: `473ebd78292f663b52a22840708e8d0a83a4828a33e64e65a40d042fd391841a`
- Size: approximately 136 KiB

## Privacy

The scan represents a real private room and can reveal room geometry and furniture placement. This repository is public, so treat any future raw scan upload as public data.

## Binary asset note

The ChatGPT GitHub connector used for this session can create/update repository text content, branches, commits and Git objects, but the available write interface does not accept a local binary file reference directly. For that reason, the raw GLB bytes are not embedded in this commit; the public Polycam capture above is retained as the source reference and the GLB-derived structured measurements are committed in `analysis/measurements.yaml`.

When adding the raw binary manually, use:

```text
data/room-scan.glb
```

and verify the SHA-256 above after upload.
