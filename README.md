Mudi Jyolsan (മുടി ജ്യോത്സൻ) 🎯

Basic Details

Team Name: Nexheim

Team Members

Team Lead: Tilin Bijoy - Viswajyothi College of Engineering and Technology, Vazhakulam

Member 2: Avin Suresh - Viswajyothi College of Engineering and Technology, Vazhakulam

Project Description

Mudi Jyolsan is a next-generation, AI-powered wellness application that provides users with a hyper-personalized analysis of their hair. By uploading four images of their head, users receive a precise, data-driven hair count, a 3D follicular density heatmap, and a unique AI-generated "prophecy" about their future.

The Problem (that doesn't exist)

For centuries, humanity has stared into the mirror, plagued by a single, agonizing question: "Exactly how many strands of hair are on my head, and what does it mean for my destiny?" This critical gap in self-awareness leads to existential dread and suboptimal life choices. Traditional methods are inefficient, and society has lacked a data-driven solution to this follicular crisis.

The Solution (that nobody asked for)

We have engineered the world's first Psychofollicular Analysis Engine. Our platform leverages a proprietary, multi-stage computer vision algorithm to perform a 360° volumetric hair census. The results are cross-referenced with our advanced AI oracle, providing users with not just a number, but a profound, actionable "hair prophecy" to guide their lives.

Technical Details

Technologies/Components Used

For Software:
Languages: TypeScript, Python

Frameworks: Next.js, React

Libraries:

Frontend: Tailwind CSS, React-Three-Fiber, Drei, Framer Motion

Backend (Python): OpenCV, NumPy, Matplotlib, Seaborn

AI: Google Generative AI (for Gemini API)

Tools: Vercel (for deployment), Git & GitHub, VS Code

For Hardware:
This is a software-only project. The only hardware required is a standard laptop and a camera to take pictures of your head.

Implementation

For Software:

Installation



Bash



# 1. Clone the repository

git clone <your-repo-link># 2. Install frontend dependencies

npm install# 3. Install Python dependencies

pip install -r requirements.txt

Run



Bash



# Run the Next.js development server

npm run dev

Project Documentation

For Software:

Screenshots

Caption: The main upload interface, where the user is prompted to provide four images for the "360° Volumetric Scan."

Caption: The results dashboard displaying the hyper-precise "Estimated Hair Count," the scientific classification, and the interactive 3D heatmap visualization.

Caption: The AI-generated "Follicular Prophecy," revealed after the user consults the cosmos for their hair-based destiny.

Diagrams

Caption: The project architecture. The Next.js frontend calls a Node.js API route, which then uses a Python bridge to execute the OpenCV analysis script. The result, including heatmap URLs, is returned to the frontend for display.

Project Demo

Video: https://youtu.be/U6ed5QLnWGU : This video demonstrates the full user journey: uploading the four required images, the "analysis" loading screen, the dramatic reveal of the hair count and 3D model, and finally, generating the AI prophecy.

Team Contributions

Tilin Bijoy: Team Lead; managed the overall project architecture, frontend development with Next.js and React, and UI/UX design.

Avin Suresh: Backend and Algorithm Specialist; developed the core Python computer vision algorithm for hair segmentation and density analysis, and implemented the Python-Node.js bridge.


vercel link : https://useless-hair-8t8z-q69osgquo-kkrs-projects-dc28afa5.vercel.app?_vercel_share=J52NzvKYVJI6J2uQcuMlUD7jvDkj3zFI
