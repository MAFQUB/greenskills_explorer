# GreenSkills NI Explorer
An interactive, single-page dashboard designed to map and report on professional "Management and Design" courses at Queen's University Belfast (QUB) and Ulster University (UU). 
This tool supports the Department for the Economy (DfE) GreenSkills Action Plan, specifically focusing on the decarbonisation of housing stock and energy efficiency.
## Purpose
The transition to a net-zero housing stock requires more than just installation trades; it requires a professional "instruction layer" of architects, engineers, and project managers. This explorer identifies the higher education pathways that produce the professionals capable of:Design: Specifying building fabric and low-carbon technology.Analysis: Performing carbon auditing and EPC assessments.Management: Navigating funding, logistics, and regulatory compliance.
## Features
Interactive Navigation: Filter by university or search by course title, lead academic, or specific skill tags.
Secure Contact Info: Academic leads' email addresses are obfuscated (Base64) to prevent automated web scraping and spam while remaining accessible to human users.
Responsive Design: Optimized for desktop and mobile viewing.GitHub Pages Ready: A single-file HTML architecture for instant deployment.
## Updating the Dashboard
This project is built as a "data-in-code" application. To update the courses: Open index.html.Locate the const course Data array in the <script> tag. Add, edit, or remove course objects within that array. If adding new emails, convert them to Base64 (e.g., using an online tool) to maintain anti-spam protection. 
## Attribution
This project was developed with the assistance of Gemini, an AI model by Google. This tool is a collaborative artifact for QUB staff working with the Department for the Economy (DfE) on Northern Ireland's GreenSkills transition.
