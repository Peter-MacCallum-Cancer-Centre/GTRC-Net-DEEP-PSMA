# GTRC-Net-DEEP-PSMA
Pretrained weights included for PSMA and FDG PET/CT Modalities based on the <b>[DEEP-PSMA Grand Challenge](https://deep-psma.grand-challenge.org/)</b> training set.

Final weights included in manuscript based on ~400-650 cases per modality (PSMA PET, FDG PET, LuPSMA SPECT) to be available at end of challenge in September 2025


To download with pre-trained weights download by command line with git LFS (Large File Storage). Ensure git lfs is [installed](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage) and clone from command:
```
git lfs clone https://github.com/Peter-MacCallum-Cancer-Centre/GTRC-Net-DEEP-PSMA.git
```


To run inference skip the numbered pre-processing and training scripts and adapt the inference function in GTR_Infer.py
