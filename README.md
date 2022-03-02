Repo of the project 
# "Team Creative Quantum AI: Schrödinger's Game of Life"

## Installation

new conda env:
```
conda create --name qcml python=3.8
conda activate qcml
```

pip installs:
```
# panda3d & gym libs:
pip install panda-gym[extra]
pip install panda3d==1.10.11

# torch & tf libs with cuda:
pip install tensorflow-gpu
conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch

# quantum libs:
pip install qiskit
pip install kaleidoscope
```

install 3rd party SDKs:
- [panda3d SDK](https://www.panda3d.org/)
- [blender SDK](https://www.blender.org/download/)

test installation:
- run [panda-gym render example](https://github.com/qgallouedec/panda-gym/blob/cbbe9deb85f53d6f4f805917781857cdce0af957/examples/rgb_rendering.py)
- run [follow example](https://github.com/hannahaih/CreaQAI/blob/main/work_in_progress/scripts/follow.py) and try different models (line 92)
```
Actor("../models/slug2smaller",
            {"run":"../models/slug2smaller-MOVE",
             "walk":"../models/slug2smaller-MOVE"})
```
             


## Repo Contents

#### 3rd party repos:
- [l_sim repo](https://github.com/hypoid/l_sim)
- [panda-gym repo](https://github.com/qgallouedec/panda-gym)
- [phobos repo](https://github.com/dfki-ric/phobos)

# Further Information

- [Project Page](https://devpost.com/software/creative-quantum-ai)
- [Project Drive Folder](https://drive.google.com/drive/folders/1AAVX_awl2-ppt3oPYzSQJgmxsRefdhmz?usp=sharing)
