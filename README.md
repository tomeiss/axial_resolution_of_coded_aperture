# axial_resolution_of_coded_aperture
This is the repository to our article **"Assessment of the Axial Resolution of a Compact Gamma Camera With Coded Aperture Collimator"**. \
**Abstract**\
**Purpose:** Handheld Gamma cameras with coded aperture collimators are under investigation for intraoperative imaging in nuclear medicine, because they offer a high sensitivity and the possibility of 3D imaging. We assessed axial resolution and computational performance for imaging with a high resolution CA mask and a semiconductor pixel detector.\
**Methods:** To assess the axial resolution an experimental Gamma camera was set up consisting of a Timepix3 detector with a resolution of 256 × 256 pixels and a coded aperture MURA mask of rank 31 with round holes of 0.08 mm in diameter in a 0.11 mm thick Tungsten sheet. A set of measurements was taken where a point-like Gamma source was placed centrally at 21 different positions within the range of 12 to 100 mm. For each source position, the detector image was reconstructed in 0.5 mm steps surrounding the true position, resulting in a stack of images. The axial resolution was assessed by the full width at half maximum (FWHM) of the contrast-to-noise ratio (CNR) profile along the z-axis of the stack. Two different reconstruction methods were compared: MURA Decoding and a 3D maximum likelihood expectation maximization algorithm (3D-MLEM). \
**Results:** While taking x-times longer in computation, 3D-MLEM yields a smaller axial FWHM and a higher CNR. The axial resolution decreases from 4.7 mm and 1.6 mm at 14 mm to 39.5 mm and 11.6 mm at 100 mm for MURA Decoding and 3D-MLEM respectively. \
**Conclusion:** 3D-MLEM offers a better resolution but is computationally much slower than MURA decoding, whose reconstruction time is compatible with real-time imaging. Further investigations regarding the intraoperative application are required.
