# Herculaneum Scroll Labels

<img src="Images/predictions_20241113090990_nbscroll5model5_cropped.png" width="800"/>

This repository contains labels used to train Machine Learning (ML) models that detect ink in the virtually unrolled Herculaneum Scrolls. These labels (in the form of hand drawn letters and letter-shapes) are hypotheses of where the ink is in the scroll. Better labels can lead to better ML images and therefore more recovered text! The exploration of this scroll is at a very early stage, so there is much room for improvement!

This repository also contains very preliminary transcriptions of the ML images of P.Herc. 172 (Scroll 5), generated by training models on these labels. The transcriptions correspond to some of the P.Herc. 172 segments released by the Vesuvius Challenge Team.

## Machine Learning Images

The images and model checkpoints on which the transcriptions and readings are based can be found [here](https://1drv.ms/f/s!Ai-KONLxw0Srh9Y4sY-mRkeemqAM6Q?e=kCORBM).

These images and checkpoints were generated by the [Grand-Prize-Winning Model](https://github.com/younader/Vesuvius-Grandprize-Winner), trained on these ink labels and corresponding segments of the [Scroll 5 Dataset](https://dl.ash2txt.org/full-scrolls/Scroll5/). 

## Thanks

With many thanks to the [Vesuvius Challenge Team](https://scrollprize.org/) for providing the Scroll 5 Dataset (CC BY-NC 4.0), the foundation of this small contribution, and whose tireless effort has made reading these scrolls possible. The first letters in P.Herc. 172 were [found by the Vesuvius Challenge Team](https://scrollprize.substack.com/p/first-letters-found-in-new-scroll). Thank you also to the EduceLab and Papyrology Teams.

## License

The contents of this repository and the associated ML images are licensed under CC BY-NC-SA 4.0: https://creativecommons.org/licenses/by-nc/4.0/legalcode.txt. It can be unclear on which labels a model is trained, so, as per the license, please credit this repository's contribution if using these labels (or derivative labels), readings, or associated images in your work.

## Contact

I have also created Ink labels, ML images, and transcriptions of P.Herc.Paris. 4 (Scroll 1), P.Herc.Paris. 2 Fr.143 (Fragment 2), P.Herc.Paris. 1 Fr.34 (Fragment 3), and P.Herc.Paris. 1 Fr. 4 (Fragment 4), whose datasets are licensed under the Vesuvius Challenge Data Agreement. Please get in touch with me on the Vesuvius Challenge Discord Server (@polytrope.) if you are interested in these, improving these results, or have any comments (or criticism!).

## References

Handmer, C. J. (2024, September 6). Reading ancient scrolls. Casey Handmer’s Blog. https://caseyhandmer.wordpress.com/2023/08/05/reading-ancient-scrolls/ 

Nader, Y. (2024, November 27). P.Herc. 172 Images. Model: Timesformer_Scroll5_27112024. Vesuvius Challenge Segment Browser. https://vesuvius.virtual-void.net/ 

Nader, Y., Farritor, L., & Schilliger, J. (2024). Vesuvius Grandprize winner [Software]. In GitHub. https://github.com/younader/Vesuvius-Grandprize-Winner 

Parsons, S., Parker, C. S., Chapman, C., Hayashida, M., & Seales, W. B. (2023). EduceLab-Scrolls: Verifiable Recovery of Text from Herculaneum Papyri using X-ray CT. arXiv (Cornell University). https://doi.org/10.48550/arxiv.2304.02084 

Scroll 5 Dataset. (n.d.). [Dataset]. Vesuvius Challenge Team. https://dl.ash2txt.org/full-scrolls/Scroll5/
Vesuvius Challenge. (2024, November 27). First letters found in new scroll. Vesuvius Challenge Newsletter. https://scrollprize.substack.com/p/first-letters-found-in-new-scroll
