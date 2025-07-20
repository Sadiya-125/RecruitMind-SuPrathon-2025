# RecruitMind: AI-Powered Resume Analyzer

An AI-powered Resume Analyzer with React, React Router, and Puter.js! Create job listings, upload candidate resumes, and use AI to automatically evaluate and match resumes to job requirements.

## Features

- Create and manage job listings
- Upload candidate resumes for analysis
- AI-powered evaluation and matching of resumes to job requirements
- Built with React, React Router, and Puter.js
- Responsive and user-friendly interface

## Setup Instructions

### Prerequisites

- Node.js (version 20 or later recommended)
- npm (comes with Node.js)
- Docker (optional, for containerized deployment)

### Local Development

1. Clone the repository:

   ```bash
   git clone https://github.com/Sadiya-125/RecruitMind-SuPrathon-2025.git
   cd RecruitMind-SuPrathon-2025
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:3000` (or the port shown in the terminal).

### Build and Production

1. Build the project:

   ```bash
   npm run build
   ```

2. Start the production server:

   ```bash
   npm run start
   ```

### Docker

To build and run the project using Docker:

1. Build the Docker image:

   ```bash
   docker build -t ai-resume-analyzer .
   ```

2. Run the Docker container:

   ```bash
   docker run -p 3000:3000 ai-resume-analyzer
   ```

3. Access the app at `http://localhost:3000`.

## Usage

- Use the web interface to create job listings.
- Upload candidate resumes in supported formats.
- The AI will analyze and score resumes, helping you find the best matches.
