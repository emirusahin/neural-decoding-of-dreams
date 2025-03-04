# Neural decoding of Dreams 
Emir Sahin 
<br>
## Introduction 
According to van Gerven, Seeliger, Güçlü, & Güçlütürk (2019), "neural decoding refers to the 
extraction of semantically meaningful information from brain activity patterns". This method 
provides a framework for addressing a fundamental question in neuroscience: how does the brain 
encode sensory and motor experiences through its activity? Neural decoding interprets which 
properties of stimuli are encoded in specific brain regions, offering insights into cognitive processes 
such as imagery, memory, and dreaming (van Gerven et al., 2019 p. 379). 
<br><br>
Machine learning is a common approach for creating "neural decoders". These algorithms 
are trained to predict stimuli from previously observed brain activity for different stimuli (van Gerven 
et al., 2019). The methods have demonstrated various levels of statistically significant success in 
decoding multiple modalities in multiple contexts. Horikawa et al. (2013) decoded visual stimuli in 
dreams. In non-sleep-related areas, Bellier et al. (2023) reconstructed music from brain activity, 
and Güçlütürk et al. (2017) reconstructed pictures of observed faces. 
<br><br>
This paper focuses on the application of neural decoding to dream research. By examining 
current methodologies and identifying limitations, this paper explores the future potential of 
decoding abstract and multimodal experiences during sleep. 
<br><br>
## Neural decoding of Dreams 
Research on the neural decoding of dreams is an emerging field, with a limited number of 
laboratories actively contributing to this area. Notably, the Kamitani Laboratory at Kyoto University 
has made significant strides in decoding visual imagery during sleep (Horikawa et al., 2013). Most 
published studies have concentrated on reconstructing visual aspects of dream content. For 
example, Horikawa and Kamitani demonstrated the ability to predict dreamed objects from brain 
activity during sleep (Horikawa & Kamitani, 2016). However, a comprehensive decoder capable of 
simultaneously reconstructing multiple facets of dream content—such as imagery; auditory, 
olfactory, and gustatory experiences; and motor activities—has yet to be developed. Current 
methodologies focus primarily on visual elements, leaving other sensory and cognitive aspects less 
explored. In this section, we analyze the progress in decoding visual stimuli from dreams and 
discuss the potential for integrating other sensory modalities into future dream decoding research. 
<br><br>
### Decoding Visual Stimuli in Dreams 
Horikawa et al. (2013) explored how the brain represents visual content during dreams, 
using machine-learning models to decode neural activity. The authors focused on the hypnagogic 
phase, the transitional period between wakefulness and sleep, where dreaming often occurs. The 
participants were frequently awakened during this phase to report their visual experiences, which 
were then mapped onto a lexical database of visual concepts. Functional magnetic resonance 
imaging (fMRI) data collected immediately before awakening were used to identify patterns of brain 
activity associated with specific visual imagery. 
<br><br>
Horikawa et al. (2013) hypothesized that the visual cortical activity associated with 
perception while awake might share patterns with visual imagery during sleep. To test this, they 
trained decoding models on brain activity induced by viewing real images. These models were then 
applied to brain activity recorded during sleep, with the aim of classifying and identifying dream 
content. 
<br><br>
The study demonstrated that decoding visual content during dreams via brain activity 
patterns is feasible, achieving an average accuracy of 60% for distinguishing between two visual 
categories, significantly exceeding the chance level of 50%. For pairs of visual categories that were 
more distinct, the accuracy improved to approximately 70%. High-level visual cortical regions, such 
as the lateral occipital complex and fusiform face area, showed better decoding performance than 
lower-level areas, such as the primary visual cortex, which is consistent with their role in 
processing complex, object-level features. When multiple visual elements were examined 
simultaneously, decoding performance varied across categories, with some exceeding chance 
levels. Importantly, the study highlighted a strong overlap in brain activity patterns between wakeful 
perception and dream imagery, reinforcing the hypothesis that shared neural mechanisms underlie 
both experiences (Horikawa et al., 2013). 
<br><br>
In a follow-up study, Horikawa & Kamitani (2016) extended this work by incorporating 
features derived from deep neural networks (DNNs) to investigate hierarchical visual 
representations in the brain. Using decoders trained on DNN-derived features from perception 
experiments, the authors tested their ability to decode visual features of dreamed objects. They 
reported significant positive correlations between decoded features and actual object features in 
higher visual areas, particularly at mid- to high-level DNN layers. They also showed that dreamed 
object categories could be identified at above-chance levels, with certain brain regions (such as the 
lateral occipital complex and fusiform face area) outperforming others. This study demonstrated 
that dreams recruit hierarchical visual representations similar to those involved in perception 
(Horikawa & Kamitani, 2016). 
<br><br>
### Extending neural decoding to other modalities of dreaming 
While visual stimuli in dreams can be decoded above chance levels, the decoding of other 
modalities, such as motor, auditory, olfactory, and gustatory experiences, remains underexplored. 
However, advancements in related areas suggest potential pathways for future research. 
Dresler et al. (2011) investigated the activation of the sensorimotor cortex during dreamed 
movements in lucid dreaming participants. By comparing brain activity during dreamed hand 
clenching, imagined hand clenching, and actual hand clenching, researchers have identified 
significant overlap in activation patterns. Notably, activation was strongest during actual 
movements, followed by dreamed and imagined movements. This study highlights the potential for 
decoding motor-related dream activity, but the reliance on lucid dreaming participants raises 
questions about whether such findings can be generalized to nonlucid dreamers. Future studies 
should use nonlucid dreaming participants and detailed dream reports to validate these findings. 
In nondream contexts, researchers have successfully decoded motor activities with varying 
degrees of accuracy. For example, upper-limb movements such as hand grasping and elbow flexion 
were decoded with 66% accuracy (Sugata et al., 2012), whereas directional reaching (up, down, 
left, right) was decoded at 39.5% accuracy, significantly above the 20% chance level (Shiman et al., 
2015). Finer movements, including single-finger flexion, single-finger extension and two-finger 
combinations, achieved accuracies as high as 99% when activation patterns of approximately 30 
neurons were used (Shin et al., 2009). While these studies do not directly address dream decoding, 
the strong correlations between awake and dreamed motor activity, as demonstrated by Dresler et 
al. (2011), suggest that similar methods could be applied to dream decoding. 
<br><br>
The extension of decoding techniques to auditory, olfactory, and gustatory modalities 
presents additional challenges. King (2006) demonstrated that auditory imagery, such as imagining 
or anticipating sounds, elicits neural activity patterns in the auditory cortex similar to those evoked 
by actual auditory stimuli. Moses et al. (2019) decoded spoken and heard speech components in 
real- time, whereas Bellier et al. (2023) reconstructed music via nonlinear decoding algorithms. 
Although these studies provide valuable insights, the lack of direct evidence linking brain activity 
during dreamed auditory experiences to waking experiences limits their applicability to dream 
decoding. Future research should prioritize identifying overlaps between real and dreamed auditory 
stimuli to establish a foundation for decoding dreamed auditory content. 
<br><br>
Olfactory and gustatory modalities are even less explored in the context of neural decoding. 
Bensafi et al. (2003) reported that imagining odors activates neural substrates in the piriform 
cortex, similar to actual olfactory perception. However, there is no evidence yet connecting such 
activation patterns to dreamed olfactory experiences. Similarly, research on decoding gustatory 
perception remains sparse, with little to no exploration of its potential application to dreams. Given 
that visual and auditory experiences dominate dream content (Zadra et al., 1998), the limited focus 
on olfactory and gustatory decoding is perhaps unsurprising. Nevertheless, expanding decoding 
efforts to these modalities could enhance our understanding of the multisensory nature of 
dreaming. 
<br><br>
## Future Research 
Future research should prioritize exploring the overlaps between brain activity evoked by 
dreamed and experienced auditory, olfactory, and gustatory stimuli. The limited focus on these 
sensory modalities has restricted our understanding of the multisensory nature of dreams. 
Expanding decoding research on olfactory and gustatory perceptions is crucial to gaining a more 
comprehensive understanding of how these experiences are represented in the brain. 
<br><br>
In addition to sensory modalities, comprehensive dream decoding should emphasize more 
abstract experiences, such as inner speech, thoughts, and emotions. For example, Liwicki et al. 
(2022) successfully decoded 5 vowels and 6 words from inner speech with 35.20% and 29.21% 
accuracy, respectively. Kim et al. (2023) demonstrated the ability to decode thoughts along 
dimensions such as self-relevance and emotional valence. Among these abstractions, decoding 
the emotional content of dreams appears to be more advanced. Scarpelli et al. (2019) argued that 
similar neural substrates are involved in both dreaming and wakeful emotional regulation, 
suggesting that emotion decoding in dreams may benefit from existing research on wakeful 
emotional processing. Similarly, Lu et al. (2020) identified positive and negative emotions in awake 
subjects with 85.11% accuracy via EEG signals, highlighting the feasibility of emotion decoding in 
dream states. 
<br><br>
## Conclusion 
In this paper, we introduced the concept of neural decoding and explored its application in 
the context of dreams. We reviewed the progress in decoding various modalities of dreams, 
highlighting both achievements and current limitations. Furthermore, we identified future 
directions for research, emphasizing the potential for advancing our understanding of dreams and 
their underlying neural mechanisms. 
<br><br>
The development of more sophisticated and accurate techniques for dream decoding 
across all sensory and cognitive modalities will significantly enhance our ability to study dreams. 
These advancements could reduce reliance on subjective self-reports, minimizing the need to 
disrupt participants' sleep to gather data. Moreover, improved decoding models may enable the 
exploration of topics that are currently inaccessible, such as dreaming in animals or individuals in 
comatose states. 
<br><br>
As neural decoding technologies advance, it is critical to consider the ethical implications 
of reconstructing private mental experiences. Questions surrounding privacy, consent, and the 
regulation of such technologies must be addressed proactively to ensure their responsible use. We 
urge researchers, policymakers, and ethicists to collaborate in establishing guidelines that balance 
scientific progress with the protection of individual rights. 
By advancing dream decoding techniques and addressing the associated ethical 
challenges, this field has the potential to revolutionize dream research, providing profound insights 
into the human mind and consciousness. 
<br><br>
# References 
1. Gerven, M., Seeliger, K., Güçlü, U., & Güçlütürk, Y. (2019). Current advances in neural 
decoding. In A. Holzinger, R. Goebel, M. Mengel, & H. Müller (Eds.), _Explainable AI: 
Interpreting, explaining and visualizing deep learning_ (pp. 379–394). Springer. 
https://doi.org/10.1007/978-3-030-28954-6_21 
2. Horikawa, T., Tamaki, M., Miyawaki, Y., & Kamitani, Y. (2013). Neural Decoding of Visual 
Imagery During Sleep. _Science_, 340, 639 - 642. https://doi.org/10.1126/science.1234330. 
3. Almuhammadi, W., Aboalayon, K., & Faezipour, M. (2015). Efficient obstructive sleep apnea 
classification based on EEG signals. _2015 Long Island Systems, Applications and 
Technology_, 1-6. https://doi.org/10.1109/LISAT.2015.7160186. 
4. Güçlütürk, Y., Güçlü, U., Seeliger, K., Bosch, S., Lier, R., & Gerven, M. (2017). Deep 
adversarial neural decoding. _ArXiv_, abs/1705.07109. 
5. Shen, G., Horikawa, T., Majima, K., & Kamitani, Y. (2017). Deep image reconstruction from 
human brain activity. _PLoS Computational Biology_, 15. https://doi.org/10.1101/240317. 
6. Dresler, M., Koch, S., Wehrle, R., Spoormaker, V., Holsboer, F., Steiger, A., Sämann, P., Obrig, 
H., & Czisch, M. (2011). Dreamed Movement Elicits Activation in the Sensorimotor 
Cortex. _Current Biology_, 21, 1833-1837. https://doi.org/10.1016/j.cub.2011.09.029. 
7. Sugata, H., Goto, T., Hirata, M., Yanagisawa, T., Shayne, M., Matsushita, K., Yoshimine, T., & 
Yorifuji, S. (2012). Neural decoding of unilateral upper limb movements using single trial 
MEG signals. _Brain Research_, 1468, 29-37. 
https://doi.org/10.1016/j.brainres.2012.05.053. 
8. Shin, H., Watkins, Z., & Hu, X. (2017). Exploration of Hand Grasp Patterns Elicitable Through 
Non-Invasive Proximal Nerve Stimulation. _Scientific Reports_, 7. 
https://doi.org/10.1038/s41598-017-16824-1. 
9. Arima, M., Ogata, A., Kawahira, K., & Shimodozono, M. (2017). Improvement and 
Neuroplasticity after Combined Rehabilitation to Forced Grasping. _Case Reports in 
Neurological Medicine_, 2017. https://doi.org/10.1155/2017/1028390. 
10. Fagg, A., Ojakangas, G., Miller, L., & Hatsopoulos, N. (2009). Kinetic Trajectory Decoding 
Using Motor Cortical Ensembles. _IEEE Transactions on Neural Systems and Rehabilitation 
Engineering_, 17, 487-496. https://doi.org/10.1109/TNSRE.2009.2029313. 
11. Shiman, F., Irastorza-Landa, N., Sarasola-Sanz, A., Spüler, M., Birbaumer, N., & Ramos
Murguialday, A. (2015). Towards decoding of functional movements from the same limb 
using EEG. _2015 37th Annual International Conference of the IEEE Engineering in Medicine 
and Biology Society (EMBC)_, 1922-1925. https://doi.org/10.1109/EMBC.2015.7318759. 
12. Moses, D., Leonard, M., Makin, J., & Chang, E. (2019). Real-time decoding of question-and
answer speech dialogue using human cortical activity. _Nature Communications_, 10. 
https://doi.org/10.1038/s41467-019-10994-4. 
13. Bellier, L., Llorens, A., Marciano, D., Gunduz, A., Schalk, G., Brunner, P., & Knight, R. (2023). 
Music can be reconstructed from human auditory cortex activity using nonlinear decoding 
models. _PLOS Biology_, 21. https://doi.org/10.1371/journal.pbio.3002176. 
14. Bensafi, M., Sobel, N., & Khan, R. (2007). Hedonic-specific activity in piriform cortex during 
odor imagery mimics that during odor perception.. _Journal of neurophysiology_, 98 6, 
3254-62 . https://doi.org/10.1152/JN.00349.2007. 
15. Zadra, A., Nielsen, T., & Donderi, D. (1998). Prevalence of Auditory, Olfactory, and Gustatory 
Experiences in Home Dreams. _Perceptual and Motor Skills_, 87, 819 - 826. 
https://doi.org/10.2466/pms.1998.87.3.819. 
16. Liwicki, F., Gupta, V., Saini, R., De, K., & Liwicki, M. (2022). Rethinking the Methods and 
Algorithms for Inner Speech Decoding and Making Them Reproducible. _NeuroSci_. 
https://doi.org/10.3390/neurosci3020017. 
17. Kim, H., lLux, B., Finn, E., & Woo, C. (2023). Getting Personal: Brain Decoding of 
Spontaneous Thought Using Personal Narratives. _bioRxiv_. 
https://doi.org/10.1101/2023.05.12.540141. 
18. Scarpelli, S., Bartolacci, C., D'Atri, A., Gorgoni, M., & De Gennaro, L. (2019). The Functional 
Role of Dreaming in Emotional Processes. _Frontiers in Psychology_, 10. 
https://doi.org/10.3389/fpsyg.2019.00459. 
19. Lu, Y., Wang, M., Wu, W., Han, Y., Zhang, Q., & Chen, S. (2020). Dynamic entropy-based 
pattern learning to identify emotions from EEG signals across individuals. _Measurement_, 
150, 107003. https://doi.org/10.1016/j.measurement.2019.107003. 
