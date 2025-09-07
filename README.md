# Free Resume Builder

## Overview

Free Resume Builder is a lightweight, browser-based application that allows users to create, edit, and export professional resumes without any sign-up or subscription. It runs entirely in the browser, stores data locally, and is designed to be ATS-friendly.

## Features

* **No Sign-Up Required**: All functionality is available without creating an account.
* **Local Storage**: Resumes are saved directly in the browser's `localStorage`. No external servers are involved.
* **AI-Powered Mode**: Optionally, users can upload an existing resume (PDF or text) and use an AI model via OpenRouter to generate a structured, ATS-friendly version.
* **Offline Support**: Once loaded, the application can function offline. Users can also download and run it as a single HTML file.
* **Clean UI**: Minimalist interface inspired by modern productivity tools.
* **Export Options**: Export resumes as JSON, HTML, or print-ready PDF.
* **Privacy First**: API keys for AI integration are stored locally (if the user chooses) and are never sent to third parties beyond direct API requests.

## Installation

No installation is required. The application is deployed and accessible via Vercel:

[Live Demo](https://free-resume-builder-six.vercel.app/)

Alternatively, clone the repository and open the `index.html` file directly in your browser:

```bash
git clone https://github.com/Siddhesh2377/FreeResumeBuilder.git
cd FreeResumeBuilder
open index.html
```

## Usage

1. Open the application in your browser.
2. Use the **Editor** to create or edit a resume.
3. Save your work locally. Resumes will appear in the **Saved** section.
4. Optionally, switch to **Make with AI** mode, upload your existing resume, and provide your OpenRouter API key to generate an AI-refined resume.
5. Export your resume to JSON, HTML, or PDF.

## Technology Stack

* **Frontend**: HTML, CSS, and Vanilla JavaScript (no frameworks or build tools)
* **AI Integration**: [OpenRouter](https://openrouter.ai/) with `openai/gpt-oss-20b:free` for structured outputs
* **Hosting**: Vercel

## Roadmap

* Additional resume templates
* Multi-language support
* Enhanced print layouts (fit-to-one-page mode)
* Faster AI model options
* Template sharing via JSON import/export

## Contributing

Contributions are welcome. Please fork the repository and submit a pull request with detailed notes on changes.

## License

This project is released under the MIT License. See the LICENSE file for more information.

## Repository

[GitHub Repository](https://github.com/Siddhesh2377/FreeResumeBuilder)
