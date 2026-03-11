# GLFW Windows ARM64 Builder

GitHub Actions workflow to cross-compile GLFW for Windows ARM64 from a standard x64 runner.

## Usage

1. Go to **Settings > Actions > General > Workflow permissions** and enable **Read and write permissions**
2. Go to **Actions** > **Build GLFW for Windows ARM64**
3. Click **Run workflow**, choose the GLFW version (default: `3.4`)
4. Once complete, the built files are committed directly into the repo — just `git pull`

## Output

```
lib/
  glfw3.dll        # shared library
  glfw3dll.lib     # import library for the DLL
  glfw3.lib        # static library
include/
  GLFW/
    glfw3.h
    glfw3native.h
```
