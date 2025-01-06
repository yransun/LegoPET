# LegoPET: Hierarchical Feature Guided Conditional Diffusion for PET Image Reconstruction


This is the official pytorch implementation of the deep leraning model LegoPET for PET image reconstruction from sinograms. The paper has been accepted to ISBI 2025. The arxiv version of the paper is available [here](https://arxiv.org/abs/2411.16629).


## Code release
The code will be released soon. In the meantime, if you have any questions regarding our paper, please feel free to open a new issue here or send me an email! Thanks for your patience :).


## Abstract
Positron emission tomography (PET) is widely utilized for cancer detection due to its ability to visualize functional and biological processes in vivo. PET images are usually reconstructed from histogrammed raw data (sinograms) using traditional iterative techniques (e.g., OSEM, MLEM). Recently, deep learning (DL) methods have shown promise by directly mapping raw sinogram data to PET images. However, DL approaches that are regression-based or GAN-based often produce overly smoothed images or introduce various artifacts respectively. Image-conditioned diffusion probabilistic models (cDPMs) are another class of likelihood-based DL techniques capable of generating highly realistic and controllable images. While cDPMs have notable strengths, they still face challenges such as maintain correspondence and consistency between input and output images when they are from different domains (e.g., sinogram vs. image domain) as well as slow convergence rates. To address these limitations, we introduce LegoPET, a hierarchical feature guided conditional diffusion model for high-perceptual quality PET image reconstruction from sinograms. We conducted several experiments demonstrating that LegoPET not only improves the performance of cDPMs but also surpasses recent DL-based PET image reconstruction techniques in terms of visual quality and pixel-level PSNR/SSIM metrics. 

## Citing our work
If you find the paper useful in your research, please cite these:

            @article{sun2024legopet,
              title={LegoPET: Hierarchical Feature Guided Conditional Diffusion for PET Image Reconstruction},
              author={Sun, Yiran and Mawlawi, Osama},
              journal={arXiv preprint arXiv:2411.16629},
              year={2024}
            }



            @inproceedings{sun2024diffpet,
              title={Diffpet: A Fine Tuned Sinogram-to-PET Conditional Diffusion Model},
              author={Sun, Yiran and Mawlawi, Osama R},
              booktitle={AAPM 66th Annual Meeting \& Exhibition},
              year={2024},
              organization={AAPM}
            }




