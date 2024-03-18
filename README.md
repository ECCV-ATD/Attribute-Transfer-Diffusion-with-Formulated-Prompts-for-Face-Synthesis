# Attribute-Transfer-Diffusion-with-Formulated-Prompts-for-Face-Synthesis
![workflow.png](workflow.png)
> **Abstract:** We propose an innovative approach to address the limitations associated with real-world facial data, particularly concerning issues of data imbalance, privacy concerns, and the annotation of attributes such as ethnicity, gender, and age. Our methodology comprises two interdependent modules: the Unique Face Generator (UFG) and the Attribute-Transfer Diffusion Model (ATD). The UFG is meticulously configured to generate unique frontal faces, each precisely tailored to specified ethnicity, gender, and age intervals. Leveraging advanced techniques including ChatGPT for prompt generation, ControlNet for steering the synthesis process, and Stable Diffusion for enhanced stability and realism, the UFG ensures the creation of diverse and realistic facial representations. Subsequently, the UFG-generated faces serve as input for the ATD module, which excels in duplicating styles from a given set of reference faces onto the input face while meticulously preserving the original facial identity. Our approach not only ensures the preservation of identity information within specific demographic groups but also enhances the diversity of the generated faces, effectively mitigating issues of data imbalance and privacy concerns prevalent in real-world datasets. To evaluate the efficacy of our approach, we curated three synthetic datasets, namely Syn-MPIE, Syn-MS1M, and Syn-CASIA, and compared them with their real-world counterparts for face recognition tasks. Through comprehensive comparative analyses against state-of-the-art methods, we demonstrate the distinct advantages and efficacy of our proposed approach. By integrating cutting-edge technologies such as ChatGPT, ControlNet, and Stable Diffusion, our approach offers a novel and effective solution for generating synthetic faces with unparalleled diversity, fidelity, and utility.
>
> ## Getting Started
- Clone the repo:
    ```
    git clone https://github.com/xxxxxx321/PASL
    cd PASL
    ```
## Installation
- Python 3.7
- Pytorch 1.12.1
2. Install the requirements
   ```
    conda env create -f environment.yml
    ```
3. Please refer to [Pytorch3d](https://github.com/facebookresearch/pytorch3d/blob/main/INSTALL.md) to install pytorch3d.
## Pretrained Model
|Path|Description|
|---|---|
|[Syn MS1M Model](https://drive.google.com/file/d/10cNTvXIHllW1_rIgQovHE26_ASfKtLX7/view?usp=sharing)|Unzip it and place it into the data directory|
|[Syn CASIA Model](https://drive.google.com/file/d/1GCDhgMatmHH1LITpVgB_RTfpjAF13MXu/view?usp=sharing)|Unzip it and place it into the main directory|
|[Syn MPIE Model](https://drive.google.com/file/d/1E2GCh3mT3GcLMXNk8FgoxBph29Nwgnz1/view?usp=sharing)|Unzip it and place it into the main directory|

## Training Datasets

