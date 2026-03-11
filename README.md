# GLFW Windows ARM64 Builder

GitHub Actions workflow to compile GLFW natively on Windows ARM64.

## Usage

1. Push this repo to GitHub
2. Go to **Actions** > **Build GLFW for Windows ARM64**
3. Click **Run workflow**, choose the GLFW version (default: `3.4`)
4. Once complete, download the artifacts from the workflow run

## Artifacts

Two artifacts are produced:

- **glfw-{version}-windows-arm64** — shared library (DLL + import lib + headers)
- **glfw-{version}-windows-arm64-static** — static library (.lib + headers)
