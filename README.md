# ICTP_Embedded_Linux_workshop

Project to share the ICTP workshop example about how to use Embedded Linux with SoC-FPGA

## Vidado_HOG_example

Temporary project to explore integration with HOG

### I recommend working with Git Bash in Windows

In Git Bash:

```bash
export PATH="/c/Xilinx/Vivado/2022.2/bin:$PATH"
```

To clone the repository successfully and without errors, use the following line:

```bash
git clone -b main --recurse-submodules https://github.com/fabioc9675/ICTP_Embedded_Linux_workshop.git
```

The  `--recurse-submodules` flag ensures that all submodules are fully cloned, and the `-b main` option clones the specific branch where I am currently working with the HOG module.

### HOG Initialization

To convert an existing project into a HOG project, use the following command:

```bash
./Hog/Init.sh
```

This will scan the existing projects, and `HOG` will create a `Top` directory where all detected projects will be listed.

Then, we create the project with the following command:

```bash
./Hog/Do CREATE <project_hog>
```

`project_hog` is the name we initially gave to the project, so here you should replace it with the name of the project you are creating.
