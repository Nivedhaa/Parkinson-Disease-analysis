# Parkinson-Disease-analysis

Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of dementia is increased.

Traditional diagnosis of Parkinson’s Disease involves a clinician taking a neurological history of the patient and observing motor skills in various situations. Since there is no definitive laboratory test to diagnose PD, diagnosis is often difficult, particularly in the early stages when motor effects are not yet severe. Monitoring progression of the disease over time requires repeated clinic visits by the patient. An effective screening process, particularly one that doesn’t require a clinic visit, would be beneficial. Since PD patients exhibit characteristic vocal features, voice recordings are a useful and non-invasive tool for diagnosis. If machine learning algorithms could be applied to a voice recording dataset to accurately diagnosis PD, this would be an effective screening step prior to an appointment with a clinician.

### ATTRIBUTE INFORMATION:

<b>name</b> - ASCII subject name and recording number
<b>MDVP:Fo(Hz)</b> - Average vocal fundamental frequency
<b>MDVP:Fhi(Hz)</b> - Maximum vocal fundamental frequency
<b>MDVP:Flo(Hz)</b> - Minimum vocal fundamental frequency
<b>MDVP:Jitter(%),MDVP:Jitter(Abs),MDVP:RAP,MDVP:PPQ,Jitter:DDP</b> - Several measures of variation in fundamental frequency
<b>MDVP:Shimmer,MDVP:Shimmer(dB),Shimmer:APQ3,Shimmer:APQ5,MDVP:APQ,Shimmer:DDA</b> - Several measures of variation in amplitude
<b>NHR,HNR</b> - Two measures of ratio of noise to tonal components in the voice
<b>status</b> - Health status of the subject (one) - Parkinson's, (zero) - healthy
<b>RPDE,D2</b> - Two nonlinear dynamical complexity measures
<b>DFA</b> - Signal fractal scaling exponent
<b>spread1,spread2,PPE</b> - Three nonlinear measures of fundamental frequency variation
