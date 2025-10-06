
Abstract :

This study describes the development of a Spectral Microscopy Imaging Ellipsometer, aimed
at overcoming the challenges of traditional ellipsometry while preserving its advantages, and
enabling the measurement of non-uniform thin films. We designed a rotating compensator
ellipsometry method integrated with imaging, establishing pixel-level electric field mapping to
ensure precise measurement locations. The designed computation was validated through
measurements of various uniform thin films, demonstrating that the results from our home-made
instrument are in complete agreement with those obtained from commercially available traditional
ellipsometers.

Additionally, we developed an unsupervised learning-based ellipsometric image processing
algorithm. This algorithm successfully extracted pixel-level ellipsometric spectral features after
denoising the pixel-level electric field mapping of patterned MoS2 and patterned SiO2 non-uniform
thin films. Principal component analysis (PCA) was employed to reduce unnecessary feature
dimensions, and K-means++ clustering was performed in the principal component space to
effectively cluster pixel-level spectral features in a manner independent of pattern shapes.
Following pixel classification, a layered model of the Fresnel equation was defined for each pixel,
along with an initial thickness guess. Nonlinear fitting of the self-defined error function for the
multilayer model was performed for each pixel, achieving pixel-level non-destructive, non-contact
optical detection to obtain a thickness distribution map of non-uniform thin films.

