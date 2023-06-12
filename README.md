# Digital-human-for-generating-videos
Digital human for generating videos using 4 modules.  
1. [Vits](https://github.com/ProgrammerManstein/VITS) for tts;  
2. [3d face recon](https://github.com/ProgrammerManstein/Deep3DFaceRecon_pytorch) for 3D Facial Reconstruction;  
3. Using the outputs of 1.(audio/.wav) and 2.(face module/.mat) for training [FACIAL](https://github.com/ProgrammerManstein/FACIAL), which will synthetize headposes and expressions for digital human;  
4. [Wav2lip](https://github.com/ajay-sainy/Wav2Lip-GFPGAN) for lip movement.  
# Environmental Configuration

## System Environment Description

(1) System platform: ubuntu18.04 (Python 3.8)  

(2) Computer configuration: 12 vCPU Intel (R) Xeon (R) Platinum 8255C CPU @ 2.50GHz, NVIDIA GTX A5000 24G independent graphics card  

## System construction

VITS, Deep3D face reconstruction, and Wav2lip require installation of Cuda 11.4 and PyTorch 1.11.0. FACAIL also requires TensorFlow 1.15.5 to be installed.  
