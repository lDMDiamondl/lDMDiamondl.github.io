---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
.cv-container {
    font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    line-height: 1.6;
    color: #494e52;
}
.cv-section {
    margin-bottom: 35px;
}
.cv-section-title {
    font-size: 24px;
    font-weight: bold;
    display: flex;
    align-items: center;
    margin-bottom: 18px;
    color: #494e52;
    border-bottom: 1px solid #ccc;
    padding-bottom: 5px;
}
.cv-item {
    margin-bottom: 22px;
}
.cv-row {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-bottom: 2px;
}
.cv-main-text {
    font-weight: bold;
    font-size: 17px;
    color: #494e52;
}
.cv-sub-text {
    color: #666;
    font-style: italic;
    font-size: 15px;
}
.cv-details-text {
    font-size: 14px;
    color: #666;
    font-variant: small-caps;
    font-weight: 600;
}
.cv-container ul {
    margin: 6px 0 0 22px;
    padding: 0;
    font-size: 15px;
    color: #494e52;
}
.cv-container li {
    margin-bottom: 5px;
}
.skill-item {
    margin-bottom: 8px;
    display: flex;
}
.skill-category {
    font-weight: bold;
    min-width: 150px;
    color: #494e52;
}
.award-row {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-bottom: 5px;
    font-size: 15px;
}
.award-year {
    color: #494e52;
    margin-right: 20px;
    min-width: 40px;
}
.award-detail {
    flex: 1;
    color: #494e52;
}
.award-location {
    color: #666;
    font-style: italic;
    margin-left: auto;
}
@media (max-width: 600px) {
    .cv-row, .award-row {
        flex-direction: column;
    }
}
</style>

<div class="cv-container">

    <div class="cv-section" id="education">
        <div class="cv-section-title">Education</div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">Sejong University</span>
                <span class="cv-sub-text">Seoul, South Korea</span>
            </div>
            <div class="cv-row">
                <span class="cv-details-text">B.S in AI Robotics</span>
                <span class="cv-sub-text">Mar. 2022 - Feb. 2027 (Expected)</span>
            </div>
            <ul>
                <li>Interests: Machine Learning, Image Processing, Computer Vision, Object Detection</li>
                <li>GPA: Total 4.0/4.5, Major 4.04/4.5</li>
            </ul>
        </div>
    </div>

    <div class="cv-section" id="research">
        <div class="cv-section-title">Research Experiences</div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">MINES Lab (Advisor: Hyungseok Kim)</span>
                <span class="cv-sub-text">Sejong University</span>
            </div>
            <div class="cv-row">
                <span class="cv-details-text">Undergraduate Researcher</span>
                <span class="cv-sub-text">Dec. 2023 - Jan. 2026</span>
            </div>
        </div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">Perceptual AI LAB (Advisor: Chanho Eom)</span>
                <span class="cv-sub-text">Chung‑ang University</span>
            </div>
            <div class="cv-row">
                <span class="cv-details-text">Undergraduate Researcher</span>
                <span class="cv-sub-text">Feb. 2026 - Jul. 2026</span>
            </div>
        </div>
    </div>

    <div class="cv-section" id="projects">
        <div class="cv-section-title">Project Experiences</div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">Detection of Abnormal Human Activity Recognition</span>
                <span class="cv-sub-text">Mar. 2024 - Jan. 2025</span>
            </div>
            <ul>
                <li>Developed a system to identify and flag unusual human behaviors from real-time webcam streams for automated security monitoring.</li>
                <li>Engineered a two-stage pipeline: first, utilized YOLOv11 for efficient human detection, then processed the resulting bounding boxes with a Two-Stream CNN for detailed action classification.</li>
            </ul>
        </div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">Multimodal Wearable Visual Aid for the Visually Impaired</span>
                <span class="cv-sub-text">Feb. 2025 - Jan. 2026</span>
            </div>
            <ul>
                <li>Contributed to the development of a real-time navigational assistance system by designing and training models to detect indoor and outdoor obstacles from stereo camera input.</li>
                <li>Fine-tuned an RT-DETR model on a custom dataset of outdoor obstacles, achieving over 90% mAP50 for 5 classes and preparing the model for future deployment on an NPU.</li>
            </ul>
        </div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">AI Docent Robot for the Visually Impaired (Capstone Design)</span>
                <span class="cv-sub-text">Mar. 2026 - Jun. 2026</span>
            </div>
            <ul>
                <li>Developed an AI‑powered museum docent robot for visually impaired visitors by integrating autonomous navigation with voice‑based interactive guidance.</li>
                <li>Implemented ROS2‑based autonomous navigation and an LLM‑powered RAG pipeline for personalized artwork explanations and real‑time Q&A.</li>
            </ul>
        </div>
    </div>

    <div class="cv-section" id="publications">
        <div class="cv-section-title">Publications</div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">AI Robotic Infant and Toddlers Alert In-Home System</span>
                <span class="cv-sub-text">ICCAS 2025</span>
            </div>
            <div class="cv-row">
                <span class="cv-details-text"><u>M Kim</u>, S Lee, T Kim and H Kim (oral presentation)</span>
                <span class="cv-sub-text">Nov. 2025</span>
            </div>
            <ul>
                <li>Developed a unified vision-based system using a VideoMAE V2 backbone and low-light enhancement filter to recognize 8 baby behaviors, validating its feasibility for real-time robotic monitoring.</li>
                <li>Reviewed one of the paper submissions for ICCAS 2025.</li>
            </ul>
        </div>
    </div>

    <div class="cv-section" id="extracurricular">
        <div class="cv-section-title">Extracurricular Activities</div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">Sejong AI Circle SAI</span>
                <span class="cv-sub-text">Mar. 2025 - Feb. 2026</span>
            </div>
            <div class="cv-row">
                <span class="cv-details-text">Member</span>
            </div>
            <ul>
                <li>Led and mentored a study group of 4 junior members, focusing on foundational deep learning concepts like CNNs and RNNs.</li>
            </ul>
        </div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">Korea Electronics Technology Institute (KETI)</span>
            </div>
            <div class="cv-row">
                <span class="cv-details-text">Research Internship</span>
                <span class="cv-sub-text">Jan. 2026 - Feb. 2026</span>
            </div>
            <ul>
                <li>Developed an on‑device VLM service using Phi‑4 on Jetson Orin and Raspberry Pi.</li>
                <li>Reproduced and implemented a Visual Grounding research paper on Jetson Orin.</li>
            </ul>
        </div>
    </div>

    <div class="cv-section" id="honors">
        <div class="cv-section-title">Honors & Awards</div>
        <div class="cv-item">
            <div class="award-row">
                <span class="award-year">2025</span>
                <span class="award-detail"><strong>Bronze Award</strong>, Sejong AI Challenge 2025S</span>
                <span class="award-location">Seoul, S.Korea</span>
            </div>
        </div>
        <div class="cv-item">
            <div class="award-row">
                <span class="award-year">2025</span>
                <span class="award-detail"><strong>Gold Award</strong>, Sejong AI Challenge 2025F</span>
                <span class="award-location">Seoul, S.Korea</span>
            </div>
        </div>
    </div>

    <div class="cv-section" id="skills">
        <div class="cv-section-title">Skills</div>
        <div class="skills-container">
            <div class="skill-item">
                <span class="skill-category">Programming</span>
                <span>Python, C/C++, Java</span>
            </div>
            <div class="skill-item">
                <span class="skill-category">Deep Learning</span>
                <span>Pytorch, Tensorflow, Scikit-learn</span>
            </div>
            <div class="skill-item">
                <span class="skill-category">Data Analysis</span>
                <span>Numpy, Pandas, Matplotlib</span>
            </div>
            <div class="skill-item">
                <span class="skill-category">Languages</span>
                <span>Korean, English, Japanese</span>
            </div>
        </div>
    </div>

    <div class="cv-section" id="certifications">
        <div class="cv-section-title">Certifications</div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">TOEIC (975/990)</span>
                <span class="cv-sub-text">2025.04.13</span>
            </div>
        </div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">TEPS (403/600)</span>
                <span class="cv-sub-text">2026.03.28</span>
            </div>
        </div>
        <div class="cv-item">
            <div class="cv-row">
                <span class="cv-main-text">JLPT N1 (143/180)</span>
                <span class="cv-sub-text">2026.01.19</span>
            </div>
        </div>
    </div>

</div>
