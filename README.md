Loosh.ai Research Partner Dashboard
Overview
This project is an interactive, web-based dashboard designed to showcase Loosh.ai's capability to correlate subjective, phenomenological reports with objective neuro-biometric data. It serves as a powerful demonstration tool for potential research partners by visualizing complex consciousness data in an intuitive and compelling way.

The dashboard is built as a single, self-contained index.html file, making it easy to share, view, and deploy without requiring a complex server setup.

Live Demo: https://loosh-ai.github.io/Research-Dashboard

Features
Interactive Filtering: Users can dynamically filter the dataset by technique, reported phenomenon, and experience intensity.

Glassmorphic UI: A modern, visually appealing design using glassmorphism principles for a clean, futuristic look.

Dynamic Charting: Utilizes Chart.js to render three main visualizations that update in real-time:

Consciousness State-Space: A bubble chart mapping experiences based on EEG Theta vs. Gamma power.

Aggregate Neuro-Biometrics: A bar chart showing the average biometric values for the filtered data.

Subjective Experience Cloud: A dynamically generated word cloud from user narrative logs.

Responsive Design: The layout adapts smoothly to various screen sizes, from mobile devices to large desktop monitors.

No Dependencies: Runs entirely in the browser with no need for server-side processing or local installation.

Technology Stack
HTML5: The core structure of the document.

Tailwind CSS: A utility-first CSS framework for rapid UI development and responsive design.

JavaScript (ES6+): Handles all logic, including data parsing, filtering, and DOM manipulation.

Chart.js: A powerful and flexible library for creating the interactive data visualizations.

Google Fonts: Used for the 'Inter' font family for a clean and readable typeface.

How It Works
The entire application is self-contained within the index.html file.

Filter Population: The script dynamically generates the filter checkboxes based on the unique Technique and ReportedPhenomenon values found in the dataset.

Chart Initialization: The three Chart.js charts are initialized with their respective configurations.

Event Handling: Event listeners are attached to all filter controls (checkboxes and the intensity slider).

Update Cycle: When a filter is changed:

The full dataset is filtered based on the currently selected criteria.

The filtered data is then passed to update functions for each component on the dashboard: the global metrics, the three charts, and the word cloud.

The charts are re-rendered with the new data, providing a seamless interactive experience.
