# NeuroPulse-Parkinsons-disease
Modeling Pathological Activity in Parkinson's Disease
Overview
This project aims to simulate and analyze changes in oscillatory neural activity associated with Parkinson's disease, particularly focusing on beta-band power. The model evaluates how these changes are influenced by movement and medication and investigates motor circuit interactions with the basal ganglia during specific tasks.

Steps to Build the Computational Model
1. Data Preprocessing
Filter Local Field Potential (LFP) signals to remove noise and isolate the beta frequency band.
Segment the data into relevant conditions:
Rest vs. Movement
MedOn (with medication) vs. MedOff (without medication)
2. Feature Extraction
Analyze the Power Spectral Density (PSD) to study power distribution across frequency bands.
Measure synchrony and coherence between LFP signals from different regions to assess functional connectivity.
Identify bursts of oscillatory activity that may reflect pathological neural patterns.
3. Simulating Medication and Movement Effects
Integrate model parameters to simulate:
Medication effects: Changes in synaptic weights or neurotransmitter dynamics.
Movement-related modulation: Neural activity variations during motor tasks like static hold and fist-clenching.
4. Validation and Comparison
Compare the simulated results with real LFP recordings:
Oscillatory power changes.
Synchrony and functional connectivity patterns.
Assess differences across conditions  MedOn vs. MedOff.

Fine-tune model parameters to better fit experimental data and refine insights into Parkinson's disease neurophysiology.
