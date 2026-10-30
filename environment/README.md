# Environment provenance

The notebook records Python 3.12.16 and PyTorch 2.14.1+cpu on Windows in the Conda `ai-labs` environment. Top-level versions in `../requirements.txt` were read from that existing environment while preparing this repository. No packages were installed and no training was run during publication.

`requirements.course.lock.txt` is copied from the original group repository. It is a course dependency snapshot, not a complete freeze of the author's Windows environment: for example, it lists ipykernel 7.4.0 whereas the inspected Windows environment has 7.3.0, and contains platform-dependent packages. Use the top-level requirements and environment notes to understand provenance; do not assume this snapshot is a universal Windows installation lock.

The repository retains the original `%pip install torch==2.14.1` notebook cell. Skip it if the intended environment is already installed. Use `lab1/` as the working directory when executing the notebook.
