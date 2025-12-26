# VSGC
Paper:Visible Singularitites Guided Multi-scale Correlation Modeling Network for Limited-Angle CT Reconstruction
Authors:Yiyang Wen, Liu Shi, Zekun Zhou, WenZhe Shan, Qiegen Liu

Unpublished

Limited-angle computed tomography (LACT) offers
the advantages of reduced radiation dose and shortened scanning
time. However, data incompleteness causes images reconstructed
by traditional algorithms to suffer from blurring along the
ray normal direction and streaking artifacts at the boundaries
of limited data. Currently, most deep learning-based LACT
reconstruction methods focus on multi-domain fusion or the
introduction of generic priors, failing to fully align with the core
imaging characteristics of LACT—such as the directionality of
artifacts and directional loss of structural information—caused
by angular deficiency. Inspired by the theory of visible and
invisible singularities, we propose the Visible Singularities Guided
Multi-Scale Correlation Modeling Network (VSGC) for LACT reconstruction. The design philosophy of VSGC consists
of two core steps: first, extract visible edge features from
LACT images and focus the model’s attention on
these visible edges; second, establish all reasonable correlations
between the visible edge features and other regions of the image
as comprehensively as possible. Additionally, a multi-scale loss
function is employed to constrain the model to converge in
multiple aspects. Finally, qualitative and quantitative validations
are conducted on both simulated and real datasets to verify the
effectiveness and feasibility of the proposed design.
<img width="3113" height="2020" alt="limited-angle" src="https://github.com/user-attachments/assets/9cf03936-45b5-4912-8a65-dd0f00486afb" />


This is a deep learning network designed to consider the characteristics of limited angular imaging (with directional anisotropy) and is used for the reconstruction of LACT.
