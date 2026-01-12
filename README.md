# 20251R0136COSE47400
## Solving Scale Variation in Crowd Density Estimation using CSRNet and CBAM
Team Member: 
Mahirah Sofea, Nur Mushira, Julia Irsalina

### Introduction 
The Congested Scene Recognition Network, CSRNet is a deep learning model that performs well in crowd density estimation by using dilated convolutions to capture pat- terns at different scales. However, it struggles when crowd size varies greatly within an image. To address this, we propose a global Gaussian technique during data prepara- tion to help the model better supervise and capture blur in the front region. On the model side, we integrate a Convo- lutional Block Attention Module (CBAM) into CSRNet to help it focus on more important areas in both channel and spatial dimensions.

Our training history (log) of loss is in training_CSRNET.ipynb and training_CBAM.ipynb.
These are the links to our checkpoint and best model .pth.tar
1. CSRNet + Geo-Adaptive
  - checkpoint: https://drive.google.com/file/d/1xNVFGn8wsKDHnT4JmbxRdCfhOKHpU7Dz/view?usp=sharing
  - best model: https://drive.google.com/file/d/1b-lg_UV4-xtP6XseOtanNfW_2iElo9QS/view?usp=sharing
2. CSRNet_CBAM + Geo-Adaptive
  - checkpoint: https://drive.google.com/file/d/1DVmmt4J2nDYhAD95HC75RtMOgU2Mh9bi/view?usp=sharing
  - best model: https://drive.google.com/file/d/1738hUa1ugzZd4i1b-J8ddVzJmdSeWvrm/view?usp=sharing
3. CSRNet + Global
  - checkpoint: https://drive.google.com/file/d/1fWl_PSmzVgFPoe-C_mBuhvErX1M-GNbc/view?usp=sharing
  - best model: https://drive.google.com/file/d/10N9H5Xr46ELx2EBr6TZhp7_i_cG2BaN2/view?usp=sharing
4. CSRNet_CBAM + Global
  - checkpoint: https://drive.google.com/file/d/19vdco68_HKYQkuwyNDlVFRBdlreAwOqe/view?usp=drive_link
  - best model: https://drive.google.com/file/d/1CDfStLM2kDpKNwUfjHWbLhJd1lPzqqSl/view?usp=sharing
