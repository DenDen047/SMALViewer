# SMALViewer
PyQt5 app for viewing SMAL meshes

## Installation
1. Clone the repository with submodules and enter directory
   ```
   git clone --recurse-submodules https://github.com/benjiebob/SMALViewer
   cd CreaturesResult
    
2. Install the Neural Mesh Renderer submodule (which originated from my [fork](https://github.com/benjiebob/neural_renderer)), which includes a render_points function

   ```
   pip install -e neural_renderer

3. Download texture map (from smal/dog_texture.pkl) and a version of SMAL 2017 converted to NumPy (smal_CVPR2017_np.pkl) from [my Google Drive](https://drive.google.com/open?id=1gPwA_tl1qrKiUkveE8PTsEOEMHtTw8br) and place under the smal folder

4. Visit the [SMAL](http://smal.is.tue.mpg.de/) website and download the smal_CVPR2017_data.pkl file. Be careful!

5. Install dependencies, particularly [PyTorch (with cuda support)](https://pytorch.org/) and PyQt5.

6. Test the python3 script
   ```
   python smal_viewer.py
   ```