PROJECT(report NONE)
cmake_minimum_required(VERSION 3.0)

INCLUDE(UseLATEX.cmake)

SET(LATEX_OUTPUT_PATH output)

ADD_LATEX_DOCUMENT(butterworth_hochpass.tex IMAGES images/butterworth-pole.png)
ADD_LATEX_DOCUMENT(butterworth_tiefpass.tex IMAGES images/butterworth-pole.png)
ADD_LATEX_DOCUMENT(digitale_filter.tex IMAGES images/ma2_ab.png images/ma2_ab_spiegel.png images/digitale_filter_rueckkopplung.png images/parallel_ap1_1.png images/parallel_ap1_2.png images/parallel_ap2_1.png images/parallel_ap2_2.png images/parallel_tp1.png images/parallel_hp1.png images/parallel_eq2.png)
ADD_LATEX_DOCUMENT(grundbegriffe.tex IMAGES images/p-ebene.png)
ADD_LATEX_DOCUMENT(tiefpass-bandpass-transformation.tex IMAGES images/tiefpass-bandpass-transformation.png)
ADD_LATEX_DOCUMENT(tiefpass-bandsperre-transformation.tex IMAGES images/tiefpass-bandsperre-transformation.png)
ADD_LATEX_DOCUMENT(tschebyscheff_hochpass.tex)
ADD_LATEX_DOCUMENT(tschebyscheff_tiefpass.tex)
ADD_LATEX_DOCUMENT(tschebyscheff_typ2_hochpass.tex)
ADD_LATEX_DOCUMENT(tschebyscheff_typ2_tiefpass.tex)

