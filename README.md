# CMakeProjectTemplate
A well-structured modern cmake template for new projects providing testing with coverage, formatting along cppcheck, benchmarking, documentation generation, and more.

The contents of `./.devcontainer` are used to create a cross-platform containerized development environment using the provided `Dockerfile`. If you are using vscode, look into *Remote Development* extension.

- Read the `./INSTALL` and provide dependencies.
- Change `MY_PROJECT_NAME` and `MY_PACKAGE_NAME` variables at primary CMakeLists.txt.
- Add your name and email to the `./cmake/Install.cmake` file.
- You should be good to go!
