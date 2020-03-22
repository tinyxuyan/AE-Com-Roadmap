# <span id = "jump">AE-Com-Roadmap</span>
Collections of Papers and Codes about Communication Systems Built by Autoencoder  


<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [<span id = "jump">AE-Com-Roadmap</span>](#span-id-jumpae-com-roadmapspan)
	- [Introduction - original Work](#introduction-original-work)
	- [Code Design](#code-design)
	- [Constellation Design](#constellation-design)
	- [Joint Source-Channel Coding](#joint-source-channel-coding)
	- [OFDM](#ofdm)
	- [MIMO](#mimo)
	- [Non-linear Channels](#non-linear-channels)
	- [Non-differential Channels](#non-differential-channels)
	- [Waveform-based AE](#waveform-based-ae)
	- [CNN-RNN structure](#cnn-rnn-structure)
	- [Optical Fibre Communications](#optical-fibre-communications)
	- [Optical Wireless Communications](#optical-wireless-communications)
	- [AE IT theory](#ae-it-theory)
	- [Security](#security)
	- [Hardware Implementation](#hardware-implementation)
	- [Others](#others)

<!-- /TOC -->

## Introduction - original Work  
[back to content](#AE-Com-Roadmap)
- T. O’Shea and J. Hoydis, “**An Introduction to Deep Learning for the Physical Layer**”, IEEE Trans. Cogn. Commun. Netw., vol. 3, no. 4, pp. 563–575, Dec. 2017.  

| Class |  Links | Description |  
|-|-|-|  
| _paper_ | [[Arxiv](http://arxiv.org/abs/1702.00832)][[IEEE](http://ieeexplore.ieee.org/document/8054694/)] | original work of autoencoder communication systems |  
| _code_ | [gram_ai](https://github.com/gram-ai/radio-transformer-networks)| Pytorch implementation
| - | [immortals](https://github.com/immortal3/AutoEncoder-Based-Communication-System) | TensorFlow 1.X version |  
| - | [FassyGit](https://github.com/FassyGit/ML-in-physical-layer) | Undergrade thesis
| - | [musicbeer](https://github.com/musicbeer/Deep-Learning-for-the-Physical-Layer) | Pytroch implementation |  
| - | [mikepatel](https://github.com/mikepatel/Deep-Learning-and-Communications-Systems) | add rayleigh fading |  


## Code Design
[back to content](#AE-Com-Roadmap)
- M. Kim, N. I. Kim, W. Lee, and D. H. Cho, “**Deep Learning-Aided SCMA**”, IEEE Commun. Lett., vol. 22, no. 4, pp. 720–723, 2018. [[IEEE](https://ieeexplore.ieee.org/document/8254356/)]
- R. Fritschek, R. F. Schaefer, and G. Wunder, “**Deep Learning for the Gaussian Wiretap Channel**”, IEEE Int. Conf. Commun., pp. 1–6, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8761681/)]
- K. L. Besser, C. R. Janda, P. H. Lin, and E. A. Jorswieck, “**Flexible Design of Finite Blocklength Wiretap Codes by Autoencoders**”, ICASSP, IEEE Int. Conf. Acoust. Speech Signal Process. - Proc., vol. 2019-May, pp. 2512–2516, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8683409/)]
[[Code](https:// gitlab.com/klb2/autoencoder-wiretap)]
- K. L. Besser, P. H. Lin, C. R. Janda, and E. A. Jorswieck, “**Wiretap Code Design by Neural Network Autoencoders**”, IEEE Trans. Inf. Forensics Secur., vol. PP, no. c, p. 1, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8859269/)]
- J. Lin, S. Feng, Y. Zhang, Z. Yang, and Y. Zhang, “**A novel deep neural network based approach for sparse code multiple access**”, Neurocomputing, Jun. 2019. [[Arxiv](http://arxiv.org/abs/1906.03169)]
- H. Ye, L. Liang, and G. Y. Li, “**Circular Convolutional Auto-Encoder for Channel Coding**”, 2019 IEEE 20th Int. Work. Signal Process. Adv. Wirel. Commun., pp. 1–5, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8815483/)]
- R. Fritschek, R. F. Schaefer, and G. Wunder, “**Deep Learning for Channel Coding via Neural Mutual Information Estimation**”, 2019 IEEE 20th Int. Work. Signal Process. Adv. Wirel. Commun., pp. 1–5, 2019. [[Arxiv](http://arxiv.org/abs/1903.02865)]
- J. Li and W. Cheng, “**Stacked Denoising Autoencoder Enhanced Polar Codes Over Rayleigh Fading Channels**”, IEEE Wirel. Commun. Lett., vol. PP, no. c, p. 1, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8908726/)]
- Y. Jiang, H. Kim, H. Asnani, S. Kannan, S. Oh, and P. Viswanath, “**Turbo Autoencoder: Deep learning based channel codes for point-to-point communication channels**”, no. NeurIPS, pp. 1–19, 2019. [[Arxiv](http://arxiv.org/abs/1911.03038)]
[[Code](https://github.com/yihanjiang/turboae/)]

## Constellation Design
[back to content](#AE-Com-Roadmap)
- M. Stark, F. A. Aoudia, and J. Hoydis, “**Joint Learning of Geometric and Probabilistic Constellation Shaping**”, no. 1, Jun. 2019. [[Arxiv](http://arxiv.org/abs/1906.07748)]
- T. Matsumine, T. Koike-Akino, and Y. Wang, “**Deep Learning-Based Constellation Optimization for Physical Network Coding in Two-Way Relay Networks**”, pp. 1–6, Mar. 2019. [[Arxiv](http://arxiv.org/abs/1903.03713)]
- F. Alberge, “**Deep Learning Constellation Design for the AWGN Channel with Additive Radar Interference**”, IEEE Trans. Commun., vol. 67, no. 2, pp. 1413–1423, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8490882/)]
- K. Gümüs, A. Alvarado, B. Chen, C. Häger, and E. Agrell, “**End-to-End Learning of Geometrical Shaping Maximizing Generalized Mutual Information**”, pp. 3–5, 2019. [[Arxiv](http://arxiv.org/abs/1912.05638)]
[[Code](https://github.com/kadirgumus/Geometric-Constellation-Shaping)]

## Joint Source-Channel Coding
[back to content](#AE-Com-Roadmap)
- N. Farsad, M. Rao, and A. Goldsmith, “**Deep Learning for Joint Source-Channel Coding of Text**”, ICASSP, IEEE Int. Conf. Acoust. Speech Signal Process. - Proc., vol. 2018-April, pp. 2326–2330, 2018. [[IEEE](https://ieeexplore.ieee.org/document/8461983/)]
[[Code](https://github.com/milindmrao/nlp_comm)]
- E. Bourtsoulatze, D. Burth Kurka, and D. Gunduz, “**Deep Joint Source-Channel Coding for Wireless Image Transmission**”, IEEE Trans. Cogn. Commun. Netw., vol. 5, no. 3, pp. 567–579, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8723589/)]
- D. B. Kurka and D. Gündüz, “**DeepJSCC-f: Deep Joint-Source Channel Coding of Images with Feedback**”, pp. 1–34, 2019. [[Arxiv](http://arxiv.org/abs/1911.11174)]
- G. Min, C. Zhang, X. Zhang, and W. Tan, “**Deep Vocoder: Low Bit Rate Compression of Speech with Deep Autoencoder**”, no. 61701535, pp. 372–377, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8794934/)]
- D. B. Kurka and D. Gunduz, “**Successive Refinement of Images with Deep Joint Source-Channel Coding**”, pp. 1–5, 2019.  [[IEEE](https://ieeexplore.ieee.org/document/8815416/)]
- Y. M. Saidutta, A. Abdi, and F. Fekri, “**M to 1 Joint Source-Channel Coding of Gaussian Sources via Dichotomy of the Input Space Based on Deep Learning**”, Data Compression Conf. Proc., vol. 2019-March, no. Dcc, pp. 488–497, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8712818/)]


## OFDM
[back to content](#AE-Com-Roadmap)
- A. Felix, S. Cammerer, S. Dorner, J. Hoydis, and S. Ten Brink, “**OFDM-Autoencoder for End-to-End Learning of Communications Systems**”, in IEEE Workshop on Signal Processing Advances in Wireless Communications, SPAWC, 2018, vol. 2018-June. [[IEEE](https://ieeexplore.ieee.org/document/8445920/)]
- M. Kim, W. Lee, and D. H. Cho, “**A novel PAPR reduction scheme for OFDM system based on deep learning**”, IEEE Commun. Lett., vol. 22, no. 3, pp. 510–513, 2018. [[IEEE](http://ieeexplore.ieee.org/document/8240644/)]
- J. Kim, B. Lee, H. Lee, Y. Kim, and J. Lee, “**Deep Learning-Assisted Multi-Dimensional Modulation and Resource Mapping for Advanced OFDM Systems**”, in 2018 IEEE Globecom Workshops (GC Wkshps), 2018, pp. 1–6. [[IEEE](https://ieeexplore.ieee.org/document/8644281/)]
- T. Wada, T. Toma, M. Dawodi, and J. Baktash, “**A Denoising Autoencoder based wireless channel transfer function estimator for OFDM communication system**”, in 1st International Conference on Artificial Intelligence in Information and Communication, ICAIIC 2019, 2019, pp. 530–533. [[IEEE](https://ieeexplore.ieee.org/document/8669044/)]
- T. Van Luong, Y. Ko, S. Member, N. Anh Vien, M. Matthaiou, and H. Quoc Ngo, “**Deep Energy Autoencoder for Noncoherent Multicarrier MU-SIMO Systems**”, pp. 1–10. [[Arxiv](http://arxiv.org/abs/2002.08710)]
- T. Xu and I. Darwazeh, “**Design and Prototyping of Neural Network Compression for Non-Orthogonal IoT Signals**”, Proc. IEEE Wirel. Commun. Netw. Conf. - 2019. IEEE Marrakech, Morocco. (In Press., 2019. [[IEEE](https://ieeexplore.ieee.org/document/8885830/)]


## MIMO
[back to content](#AE-Com-Roadmap)
- T. J. O’Shea, T. Erpek, and T. C. Clancy, “**Deep Learning Based MIMO Communications**”, IEEE Work. Signal Process. Adv. Wirel. Commun. SPAWC, vol. 2017-July, pp. 1–5, Jul. 2017. [[Arxiv](http://arxiv.org/abs/1707.07980)]
- T. Erpek, T. J. O’Shea, and T. C. Clancy, “**Learning a physical layer scheme for the MIMO interference channel**”, IEEE Int. Conf. Commun., vol. 2018-May, pp. 1–5, 2018. [[IEEE](https://ieeexplore.ieee.org/document/8422339/)]
- T. J. O’Shea, T. Erpek, and T. C. Clancy, “**Physical layer deep learning of encodings for the MIMO fading channel**”, 55th Annu. Allert. Conf. Commun. Control. Comput. Allert. 2017, vol. 2018-Janua, pp. 76–80, 2018. [[IEEE](http://ieeexplore.ieee.org/document/8262721/)]
- S. Xue, Y. Ma, N. Yi, and R. Tafazolli, “**Unsupervised deep learning for mu-simo joint transmitter and noncoherent receiver design**”, IEEE Wirel. Commun. Lett., vol. 8, no. 1, pp. 177–180, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8437142/)]
- D. Wu, M. Nekovee, and Y. Wang, “**Deep Learning Based Autoencoder for Interference Channel**”, no. Dl, pp. 4–9, 2019. [[Arxiv](http://arxiv.org/abs/1902.06841)]
- E. Stauffer, A. Wang, and N. Jindal, “**Deep Learning for the Degraded Broadcast Channel**”, Mar. 2019. [[Arxiv](http://arxiv.org/abs/1903.08577)]



## Non-linear Channels
[back to content](#AE-Com-Roadmap)
- E. Balevi and J. G. Andrews, “**Autoencoder-Based Error Correction Coding for One-Bit Quantization**”, pp. 1–30, 2019. [[Arxiv](http://arxiv.org/abs/1909.12120)]
- M. Arvinte, S. Vishwanath, and A. H. Tewfik, “**Deep Learning-Based Quantization of L-Values for Gray-Coded Modulation**”, 2019. [[Arxiv](http://arxiv.org/abs/1906.07849)]
[[Code](https://github.com/mariusarvinte/deep-llr-quantization)]
- D. Kim, S.-N. Hong, and N. Lee, “**Supervised-Learning for Multi-Hop MU-MIMO Communications with One-Bit Transceivers**”, IEEE J. Sel. Areas Commun., pp. 1–1, Apr. 2019. [[Arxiv](http://arxiv.org/abs/1904.03805)]
- C. Lu, W. Xu, S. Jin, and K. Wang, “**Bit-level Optimized Neural Network for Multi-antenna Channel Quantization**”, IEEE Wirel. Commun. Lett., pp. 1–1, 2019. [[Arxiv](http://arxiv.org/abs/1909.10730)]
- M. Varasteh, J. Hoydis, and B. Clerckx, “**Learning to Communicate and Energize : Modulation , Coding and Multiple Access Designs for Wireless Information-Power Transmission**”, pp. 1–30. [[Arxiv](http://arxiv.org/abs/1909.06492)]

## Non-differential Channels
[back to content](#AE-Com-Roadmap)
- M. Goutay, F. A. Aoudia, and J. Hoydis, “**Deep Reinforcement Learning Autoencoder with Noisy Feedback**”, 2018. [[Arxiv](http://arxiv.org/abs/1810.05419)]  
- T. J. O’Shea, T. Roy, and N. West, “**Approximating the Void: Learning Stochastic Channel Models from Observation with Variational Generative Adversarial Networks**”, 2018. [[Arxiv](http://arxiv.org/abs/1805.06350)]
- T. J. O’Shea, T. Roy, N. West, and B. C. Hilburn, “**Physical Layer Communications System Design Over-the-Air Using Adversarial Networks**”, pp. 1–9, 2018. [[Arxiv](http://arxiv.org/abs/1803.03145)]
- V. Raj and S. Kalyani, “**Backpropagating through the air: Deep learning at physical layer without channel models**”, IEEE Commun. Lett., vol. 22, no. 11, pp. 2278–2281, 2018. [[IEEE](https://ieeexplore.ieee.org/document/8452950/)]
- H. Ye, G. Y. Li, B. H. F. Juang, and K. Sivanesan, “**Channel Agnostic End-to-End Learning Based Communication Systems with Conditional GAN**”, 2018 IEEE Globecom Work. GC Wkshps 2018 - Proc., pp. 1–21, 2019. [[Arxiv](http://arxiv.org/abs/1807.00447)]
- Y. Yang, Y. Li, W. Zhang, F. Qin, P. Zhu, and C. X. Wang, “**Generative-Adversarial-Network-Based Wireless Channel Modeling: Challenges and Opportunities**”, IEEE Commun. Mag., vol. 57, no. 3, pp. 22–27, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8663987/)]
- F. Ait Aoudia and J. Hoydis, “**Model-free Training of End-to-end Communication Systems**”, IEEE J. Sel. Areas Commun., vol. PP, no. i, pp. 1–1, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8792076/)]


## Waveform-based AE
[back to content](#AE-Com-Roadmap)
- T. J. O’Shea, K. Karra, and T. C. Clancy, “**Learning to communicate: Channel auto-encoders, domain specific regularizers, and attention**”, in 2016 IEEE International Symposium on Signal Processing and Information Technology (ISSPIT), 2016, pp. 223–228. [[IEEE](http://ieeexplore.ieee.org/document/7886039/)]
- S. Dorner, S. Cammerer, J. Hoydis, and S. ten Brink, “**Deep Learning Based Communication Over the Air**”, IEEE J. Sel. Top. Signal Process., vol. 12, no. 1, pp. 132–143, Feb. 2018. [[IEEE](https://ieeexplore.ieee.org/document/8214233/)]
- W. Jiang, A. M. Haimovich, and O. Simeone, “**End-to-end Learning of Waveform Generation and Detection for Radar Systems**”, 2019. [[Arxiv](http://arxiv.org/abs/1912.00802)]
- J. Schmitz, C. von Lengerke, N. Airee, A. Behboodi, and R. Mathar, “**A Deep Learning Wireless Transceiver with Fully Learned Modulation and Synchronization**”, IEEE Int. Conf. Commun., pp. 1–6, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8757051/)]
- H. Wu, Z. Sun, and X. Zhou, “**Deep Learning-based Frame and Timing Synchronization for End-to-End Communications**”, J. Phys. Conf. Ser., vol. 1169, no. 1, 2019. [[IEEE](http://stacks.iop.org/1742-6596/1169/i=1/a=012060?key=crossref.f99f90af789e8d1f35ba29fa87ad5fb6)]


## CNN-RNN structure
[back to content](#AE-Com-Roadmap)
- D. J. Ji, J. Park, and D.-H. Cho, “**ConvAE: A New Channel Autoencoder Based on Convolutional Layers and Residual Connections**”, IEEE Commun. Lett., vol. PP, no. c, pp. 1–1, 2019.
[[IEEE](https://ieeexplore.ieee.org/document/8768327/)]
- B. Zhu, J. Wang, L. He, and J. Song, “**Joint Transceiver Optimization for Wireless Communication PHY Using Neural Network**”, IEEE J. Sel. Areas Commun., vol. 37, no. 6, pp. 1364–1373, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8664650/)]
- N. Wu, X. Wang, B. Lin, and K. Zhang, “**A CNN-Based End-to-End Learning Framework Toward Intelligent Communication Systems**”, IEEE Access, vol. 7, pp. 110197–110204, 2019.[[IEEE](https://ieeexplore.ieee.org/document/8755977/)]
[[Code](https://github.com/ZhangKaiyao/Deepcom/tree/master)]
- T. Mu, X. Chen, L. Chen, H. Yin, and W. Wang, “**An End-to-End Block Autoencoder For Physical Layer Based On Neural Networks**”, pp. 1–4, Jun. 2019. [[Arxiv](http://arxiv.org/abs/1906.06563)]

##  Optical Fibre Communications
[back to content](#AE-Com-Roadmap)
- B. Karanov et al., “**End-to-End Deep Learning of Optical Fiber Communications**”, J. Light. Technol., vol. 36, no. 20, pp. 4843–4855, Oct. 2018. [[IEEE](https://ieeexplore.ieee.org/document/8433895/)]
- B. Karanov, D. Lavery, P. Bayvel, and L. Schmalen, “**End-to-end optimized transmission over dispersive intensity-modulated channels using bidirectional recurrent neural networks**”, Opt. Express, vol. 27, no. 14, p. 19650, 2019. [[OSA](https://www.osapublishing.org/abstract.cfm?URI=oe-27-14-19650)]
- B. Karanov, M. Chagnon, V. Aref, D. Lavery, P. Bayvel, and L. Schmalen, “**Concept and Experimental Demonstration of Optical IM/DD End-to-End System Optimization using a Generative Model**”, pp. 1–3, 2019. [[Arxiv](https://arxiv.org/abs/1912.05146)]
- B. Karanov, G. Liga, V. Aref, D. Lavery, P. Bayvel, and L. Schmalen, “**Deep Learning for Communication over Dispersive Nonlinear Channels: Performance and Comparison with Classical Digital Signal Processing**”, 2018 Eur. Conf. Opt. Commun., pp. 1–3, Oct. 2019. [[Arxiv](http://arxiv.org/abs/1910.01028)]
- R. T. Jones, T. A. Eriksson, M. P. Yankov, and D. Zibar, “**Deep Learning of Geometric Constellation Shaping Including Fiber Nonlinearities**”, Eur. Conf. Opt. Commun. ECOC, vol. 2018-Septe, no. 1, pp. 3–5, 2018. [[Arxiv](http://arxiv.org/abs/1912.05146)]
- R. T. Jones, M. P. Yankov, and D. Zibar, “**End-to-end Learning for GMI Optimized Geometric Constellation Shape**”, pp. 1–4, 2019. [[Arxiv](http://arxiv.org/abs/1907.08535)] [[code](https://github.com/rassibassi/claude)]
- S. Li, C. Häger, N. Garcia, and H. Wymeersch, “**Achievable Information Rates for Nonlinear Fiber Communication via End-to-end Autoencoder Learning**”, 2018 Eur. Conf. Opt. Commun., vol. 2018-Septe, pp. 1–3, Apr. 2018. [[Arxiv](http://arxiv.org/abs/1804.07675)]


## Optical Wireless Communications
[back to content](#AE-Com-Roadmap)
- H. Lee, I. Lee, and S. H. Lee, “**Deep learning based transceiver design for multi-colored VLC systems**”, Opt. Express, vol. 26, no. 5, p. 6222, 2018. [[OSA](https://www.osapublishing.org/abstract.cfm?URI=oe-26-5-6222)]
- H. Lee, I. Lee, T. Q. S. Quek, and S. H. Lee, “**Binary signaling design for visible light communication: a deep learning framework**”, Opt. Express, vol. 26, no. 14, p. 18131, 2018. [[OSA](https://www.osapublishing.org/abstract.cfm?URI=oe-26-14-18131)]
- H. Lee, S. H. Lee, T. Q. S. Quek, and I. Lee, “**Deep Learning Framework for Wireless Systems: Applications to Optical Wireless Communications**”, IEEE Commun. Mag., pp. 1–7, 2018. [[Arxiv](http://arxiv.org/abs/1812.05227)]
- M. Soltani, W. Fatnassi, A. Aboutaleb, Z. Rezki, A. Bhuyan, and P. Titus, “**Autoencoder-Based Optical Wireless Communications Systems**”, in 2018 IEEE Globecom Workshops (GC Wkshps), 2018, pp. 1–6. [[IEEE](https://ieeexplore.ieee.org/document/8644104/)]
- H. Lee, T. Q. S. Quek, and S. H. Lee, “**A Deep Learning Approach to Universal Binary Visible Light Communication Transceiver**”, IEEE Trans. Wirel. Commun., pp. 1–1, 2019. [[Arxiv](http://arxiv.org/abs/1910.12048)]
- P. Miao, B. Zhu, C. Qi, Y. Jin, and C. Lin, “**A Model-Driven Deep Learning Method for LED Nonlinearity Mitigation in OFDM-Based Optical Communications**”, IEEE Access, vol. 7, pp. 71436–71446, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8726338/)]
- L. Shi et al., “**PAPR reduction based on deep autoencoder for VLC DCO-OFDM system**”, pp. 3–6, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8971873/)]
- Z. Zhu, J. Zhang, R. Chen, and H. Yu, “**Autoencoder-Based Transceiver Design for OWC Systems in Log-Normal Fading Channel**”, IEEE Photonics J., vol. 11, no. 5, pp. 1–12, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8819929/)]

## AE IT theory
[back to content](#AE-Com-Roadmap)
- V. Raj and S. Kalyani, “**Design of Communication Systems using Deep Learning: A Variational Inference Perspective**”, pp. 1–13, Apr. 2019. [[Arxiv](http://arxiv.org/abs/1904.08559)]
- S. Cammerer, F. A. Aoudia, S. Dörner, M. Stark, J. Hoydis, and S. ten Brink, “**Trainable Communication Systems: Concepts and Prototype**”, pp. 1–13, 2019. [[Arxiv](http://arxiv.org/abs/1911.13055)]
- W. Zhang, Y. Wang, C. Shen, and N. Liang, “**A Regression Approach to Certain Information Transmission Problems**”, IEEE J. Sel. Areas Commun., pp. 1–1, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8792077/)] [[Code](http://staff.ustc.edu.cn/~wenyizha/jsac19code.zip)]
- S. Molavipour, G. Bassi, and M. Skoglund, “**Conditional Mutual Information Neural Estimator**”, 2019. [[Arxiv](http://arxiv.org/abs/1911.02277)]


## Security
[back to content](#AE-Com-Roadmap)
- M. Sadeghi and E. G. Larsson, “**Physical Adversarial Attacks Against End-to-End Autoencoder Communication Systems**”, IEEE Commun. Lett., vol. 23, no. 5, pp. 847–850, 2019. [[IEEE](https://ieeexplore.ieee.org/document/8651357/)]
[[Code](https://github.com/meysamsadeghi/Security-and-Robustness-of-Deep-Learning-in-Wireless-Communication-Systems)]

## Hardware Implementation
[back to content](#AE-Com-Roadmap)
- M. Kim, W. Lee, J. Yoon, and O. Jo, “**Building Encoder and Decoder with Deep Neural Networks: On the Way to Reality**”, pp. 1–14, Aug. 2018. [[Arxiv](http://arxiv.org/abs/1902.06939)]
- F. A. Aoudia and J. Hoydis, “**Towards Hardware Implementation of Neural Network-based Communication Algorithms**”, no. Ml, pp. 1–5, Feb. 2019.
[[Arxiv](http://arxiv.org/abs/1808.02401)]


## Others
[back to content](#AE-Com-Roadmap)
- X. Chen, J. Cheng, Z. Zhang, L. Wu, and J. Dang, “**Data-Rate Driven Transmission Strategy for Deep Learning Based Communication Systems**”, no. 201806090072, pp. 1–26, 2018. [[Arxiv](http://arxiv.org/abs/1812.08869)]
- S. Park, O. Simeone, and J. Kang, “**Meta-Learning to Communicate: Fast End-to-End Training for Fading Channels**”, no. 2017, pp. 1–10, 2019. [[Arxiv](http://arxiv.org/abs/1910.09945)]
[[Code](https://github.com/kclip/meta-autoencoder)]  
- A. Mostaani and O. Simeone, “**On Learning How to Communicate Over Noisy Channels for Collaborative Tasks**”, 2019 IEEE 30th Annu. Int. Symp. Pers. Indoor Mob. Radio Commun., pp. 1–6, 2018. [[Arxiv](http://arxiv.org/abs/1810.01155)]



(This work is just based on the author's limited knowledge. If anyone has better ideas about the classification about the papers or anything else, please don't hesitate to create an issue or contact me at tinyxuyan@aliyun.com.)
