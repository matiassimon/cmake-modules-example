# C++ Modules Example with CMake

Welcome to a simple C++20 modules *hello world* example that utilizes CMake 3.28 and Clang 17. This example is conveniently provided as a [devcontainer](https://code.visualstudio.com/docs/devcontainers/containers) for seamless reproduction within Visual Studio Code.

### Environment Details

The development environment is set up with the following specifications:

* **Operating System:** Debian 12
* **CMake Version:** 3.28.0-rc5 (using Ninja as the generator)
* **Compiler:** Clang 17 and Clang tools 17
  * Obtained from [Debian Unstable, "sid"](https://wiki.debian.org/DebianUnstable)

### Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/matiassimon/cmake-modules-example.git
   cd cmake-modules-example
   ```

2. **Open in Visual Studio Code:**
   - Ensure you have the [Remote - Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) installed.
   - Open the cloned directory in Visual Studio Code.
   - When prompted, select "Reopen in Container" to utilize the provided devcontainer.

3. **Select CMake Kit:**
   - After the project is opened, a prompt saying "Select a Kit for cmake-modules-example" will appear.
   - Choose the kit "Clang 17.0.6 x86_64-pc-linux-gnu" for a correct compilation of the project using the CMake extension.

### Contributing

If you encounter issues or have suggestions for improvements, feel free to contribute by submitting pull requests or opening issues.

Happy coding!
