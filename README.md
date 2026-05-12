## bin
It mainly stores self-compiled binary files.

---

### Torch 2.11

> [!NOTE]
> Only support [sm_60, sm_120]
> 
> Build environment is [RTX Geforce 5060, Tesla P100]
> 
> CUDA version: 12.8.1
> 
> GCC version: gcc-13
> 
> Python version: 3.12
> 
> Linux version: Arch-7.0.5
> 

**wheel**
- torch-2.11.0a0+git70d99e9-cp312-cp312-linux_x86_64.whl
- torchvision-0.26.0+336d36e-cp312-cp312-linux_x86_64.whl

---

### Torch 2.11-Win

> [!NOTE]
> Only support [sm_60, sm_120]
> 
> Build environment is [RTX Geforce 5060, Tesla P100]
> 
> CUDA version: 12.9.1
> 
> GCC version: Visual Studio 2022 Community
> 
> Python version: 3.12
> 
> Windows version: Windows 11 Pro for Workstations 25H2
>
> The standard `cp312` wheel package **does not** include CUPTI; after installation, you must manually copy `cupti64_2025.2.1.dll` to the `torch\lib` directory.
>
> The `.cupti` wheel package already includes CUPTI and can be used for zero-configuration installation.
>
> Depending on your system configuration, some dependencies may still be missing. Please check your system and copy the corresponding DLL files to the `torch\lib` directory.

**wheel**
- torch-2.11.0a0+git70d99e9-cp312-cp312-win_amd64.whl
- torch-2.11.0a0+git70d99e9.cupti-cp312-cp312-win_amd64.whl

---

### Torch 2.7

> [!NOTE]
> Only support [sm_60, sm_120]
> 
> Build environment is [RTX Geforce 5060, Tesla P100]
> 
> CUDA version: 12.8.1
> 
> GCC version: gcc-13
> 
> Python version: 3.12
> 
> Linux version: Arch-7.0.5
>
> Only build Torch

**wheel**
- torch-2.7.0a0+git1341794-cp312-cp312-linux_x86_64.whl
