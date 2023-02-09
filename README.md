# Plausible May Not Be Faithful: Probing Object Hallucination in Vision-Language Pre-training

<img align="right" src="img/HKUST.jpg" width="15%"/>

Paper accepted at EACL 2023:

**Plausible May Not Be Faithful: Probing Object Hallucination in Vision-Language Pre-training**, by **[Wenliang Dai](https://wenliangdai.github.io/)**, [Zihan Liu](https://zliucr.github.io/), [Ziwei Ji](https://ziweiji.github.io/), Dan Su, [Pascale Fung](https://pascale.home.ece.ust.hk/).

## Paper Abstract

> Large-scale vision-language pre-trained (VLP) models are prone to hallucinate non-existent visual objects when generating text based on visual information. In this paper, we systematically study the object hallucination problem from three aspects. First, we examine recent state-of-the-art VLP models, showing that they still hallucinate frequently, and models achieving better scores on standard metrics (e.g., CIDEr) could be more unfaithful. Second, we investigate how different types of image encoding in VLP influence hallucination, including region-based, grid-based, and patch-based. Surprisingly, we find that patch-based features perform the best and smaller patch resolution yields a non-trivial reduction in object hallucination. Third, we decouple various VLP objectives and demonstrate that token-level image-text alignment and controlled generation are crucial to reducing hallucination. Based on that, we propose a simple yet effective VLP loss named ObjMLM to further mitigate object hallucination. Results show that it reduces object hallucination by up to 17.4% when tested on two benchmarks (COCO Caption for in-domain and NoCaps for out-of-domain evaluation).

If you work is inspired by our paper or code, please cite it, thanks!

<pre>
@article{Dai2022PlausibleMN,
  title={Plausible May Not Be Faithful: Probing Object Hallucination in Vision-Language Pre-training},
  author={Wenliang Dai and Zihan Liu and Ziwei Ji and Dan Su and Pascale Fung},
  journal={ArXiv},
  year={2022},
  volume={abs/2210.07688}
}
</pre>

## Code and Evaluation Setups
Coming soon, please stay tuned!
