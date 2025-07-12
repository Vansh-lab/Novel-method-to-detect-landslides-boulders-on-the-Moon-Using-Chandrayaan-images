# Novel-method-to-detect-landslides-boulders-on-the-Moon-Using-Chandrayaan-images
Brief about the Idea: Chandrasetu is an AI-powered system built on Chandrayaan- 2 data to detect and interpret lunar landslides and boulder hazards. It combines geospatial intelligence, solar illumination/shadow analysis, and explain able machine learning to help us not only spot lunar surface risks—but also understaand  why they occur andpredict next occurrences with real time analysis.
• Designed using open-source tools and aligned with ISRO's scientific practices, “Chandrasetu”
moves beyond static maps to offer a mission-grade solution for safe and informed lunar
exploration.

Keywords:
· Lunar Hazard Detection · Chandrayaan Data Fusion · SPICE Toolkit · Shadow Geometry · Segment
Anything · Time-Series Forecasting · Explainable AI · Knowledge Graphs · 3D Lunar Terrain · OpenSource Deployment

Opportunity should be able to explain the following:
Chandrasetu introduces a novel dual-mode AI method to detect lunar landslides and boulders using
Chandrayaan-2 images. Unlike traditional approaches that rely only on visible shadows or slope thresholds, our
system combines shadow geometry, texture-based CNNs, shape detection, and DEM-based elevation cues —
enabling it to work even in shadowless or low-contrast regions.
By fusing terrain physics (size, location, pattern, latitude, longitude, elevation, slope, aspect, roughness,
illumination angle, boulder_shadow_length, sun_angle, image_time) with deep learning models (U-Net,
DeepLabV3+), Chandrasetu identifies, explains, and forecasts hazards with scientific accuracy. It generates
annotated hazard maps, simulates time-based changes, and presents all outputs in an immersive 3D interface.

 USP
• Shadows-independent boulder detection
• Dual-mode AI adaptability
• Physics + AI fusion with explainability
• Time-series simulation of hazard evolution
• 3D interactive mapping
• Open-source, mission-ready design following ISRO-aligned standards

List of features offered by the solution
1. Dual-mode detection system
• Detects boulders and landslides using both shadow geometry and texture/shape-based visual features — works even in low-contrast
or shadowless regions.
2. AI-powered terrain hazard recognition
• Leverages deep learning models (U-Net, DeepLabV3+, CNNs) to analyse Chandrayaan-2 OHRC and TMC images.
3. Shadow geometry + solar angle estimation
• Calculates object dimensions and orientation using illumination data from the SPICE Toolkit.
4. Integrated terrain analysis
• Uses elevation and surface texture derived from OHRC + TMC fusion to understand slope, size, location, pattern, latitude, longitude,
elevation, aspect, roughness, illumination angle, boulder_shadow_length, sun_angle, image_time scarps, and impact zones.
5. Time-series forecasting of hazard zones
• Predicts how and where future landslides or boulder shifts might occur using models like Prophet.
6. Explainable AI insights
• Explains why a detection was made using Grad-CAM overlays and AI interpretability methods.
7. Interactive lunar hazard map
• Visual interface with annotated hazard markers and summaries of each detection.
8. Auto-generated readable reports
• Uses large language models like GPT-4 ,Claude. etc to generate short, clear summaries of each hazardous site.

Technologies to be used in the solution:
1. Satellite Data & Preprocessing
• Chandrayaan-2 OHRC & TMC imagery – Primary input data sources.
• QGIS – For raster handling, georeferencing, and DEM support.
• GDAL – To convert and process “.img” files and perform raster operations.
2. AI & Computer Vision
• Segment Anything (Meta AI) – For boulder and landslide segmentation.
• U-Net / DeepLabV3+ / CNNs – To detect surface features from texture and shape.
• Grad-CAM – To visualize why a prediction was made (explainability).
3. Orbital & Solar Analysis
• NASA SPICE Toolkit – For calculating solar incidence angles and shadow geometry based on image metadata.
4. Time-Series Prediction
• Facebook Prophet – For forecasting terrain evolution and future risk zones.
5. Visualization & Interface
• Streamlit – To build an interactive hazard detection dashboard.
• Folium / Kepler.gl – For map visualization with clickable detections.
• Matplotlib / Plotly – For graphing elevation, time-series, or model outputs.
6. Automation & Reporting
• GPT-4 / Claude API – For generating human-readable hazard summaries.
• LangChain (optional) – For chaining AI tools together if needed.
7. Programming Language
• Python – Core language for AI, data processing, and full-stack implementation.

References:
 Impacts Drive Lunar Rockfalls Over Billions of Years(Nature Communications, 2020)
https://www.nature.com/articles/s41467-020-16653-3
 Automatic Characterization of Boulders on Planetary Surfaces(arXiv, 2024)
https://arxiv.org/abs/2401.07528
 IROIIP Conference Article(IRO Journals, Vol. 7 No. 2)
https://irojournals.com/iroiip/article/pdf/7/2/1
 Rockfall Analysis Using Remote Sensing(Nature Scientific Reports, 2024)
https://www.nature.com/articles/s41598-024-58438-4
 ML-Based Lunar Image Segmentation(Stanford CS229 Project, 2019)
https://cs229.stanford.edu/proj2019aut/data/assignment_308832_raw/26614647.pdf
