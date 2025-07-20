# HelloOpenGL

A toy project based on [LearnOpenGL](https://learnopengl.com/).

## Dependencies

- `CMake`
- `vcpkg`
- `Ninja` (the build system, not the stealthy kind)

## Setup

First, create a `CMakeUserPresets.json` file.  
You can copy the template from the [Microsoft documentation](https://learn.microsoft.com/en-us/vcpkg/get-started/get-started?pivots=shell-powershell), and replace `<path to vcpkg>` with the actual path on your system.

Then run the following command to configure the project:

```bash
cmake --preset=default
