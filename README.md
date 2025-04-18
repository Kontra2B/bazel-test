To instal conan run `python3 -m venv conan-env`\
Switch to virtual environment with `source conan-env/bin/activate.fish` for fish, check other option for different shell\
Install conan with `pip3 install conan`\
For conan to build dependencies run `conan install . --build=missing`\
Run `VERSION=X.Y.Z ./bazel.run.sh`\
`./bazel.test.sh` for test
