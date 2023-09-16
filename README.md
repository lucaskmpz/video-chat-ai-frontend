# Video Transcription Prompt Application Frontend

Welcome to the Video Transcription Prompt Application Frontend repository! This frontend application complements the backend API, allowing users to interact with uploaded videos using predefined prompts. Below, you'll find an index and essential information about the technologies used, prerequisites, usage, and how the frontend works.

## Index

- [Technologies Used](#technologies-used)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [How It Works](#how-it-works)

## Technologies Used

### WebAssembly (ffmpeg.js)

WebAssembly is a binary instruction format that enables high-performance execution of code on web browsers. In this frontend, WebAssembly is used to run FFmpeg in the browser, allowing for video-to-audio conversion without server-side processing.

### FFmpeg.js

FFmpeg.js is a JavaScript port of the FFmpeg multimedia framework. It is employed for converting video files to audio (MP3) format directly within the browser. This technology enhances the user experience by eliminating the need for server-side video processing.

### Tailwind CSS

Tailwind CSS is a utility-first CSS framework that streamlines styling and layout development. It is used to create a responsive and visually appealing user interface for the Video Transcription Prompt Application. Tailwind CSS simplifies the process of designing and maintaining the frontend.

### Radix UI

Radix UI is a set of low-level UI primitives for building advanced design systems and components. It includes components like `Select`, `Slider`, and `Separator`, which are used in this frontend to create a consistent and user-friendly interface.

### Shaden UI

Shaden UI is a custom UI library designed to work seamlessly with Tailwind CSS and Radix UI. It simplifies UI component creation and styling while maintaining compatibility with the Tailwind CSS utility classes. Shaden UI enhances the development workflow and provides a cohesive design system for the application.

## Prerequisites

Before you can run the Video Transcription Prompt Application Frontend, ensure you have the following in place:

- **Node.js**: Install Node.js (version 14 or higher) on your local development environment.

## Usage

To use the frontend, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine.

   ```bash
   git clone https://github.com/your-username/your-frontend-repo.git
   cd your-frontend-repo
   ```

2. **Install Dependencies**: Install the required Node.js packages using npm.

   ```bash
   npm install
   ```

3. **Start the Frontend**: Launch the frontend development server using the following command:

   ```bash
   npm run dev
   ```

   The development server will start, and you can access the application in your web browser.

4. **Interact with the Application**: Use the frontend to upload videos, create transcription prompts, and generate AI completions based on the uploaded videos. The intuitive user interface simplifies the interaction process.

5. **Customization**: Customize the frontend to meet your specific requirements. You can extend functionality, enhance the user interface, or integrate additional features as needed.

## How It Works

The Video Transcription Prompt Application Frontend enhances the user experience by providing a user-friendly interface for interacting with video content. Here's how it works:

1. **Video Upload**: Users can select and upload video files in MP4 format directly from their local devices. The frontend utilizes WebAssembly and FFmpeg.js to convert the video files to audio (MP3) format within the browser.

2. **Transcription Prompt**: Users can input transcription prompts, specifying keywords or phrases to guide AI interactions. The application also supports predefined prompts, making it easy for users to start conversations.

3. **AI Completion Generation**: Users initiate AI completion generation by selecting a prompt and adjusting the temperature parameter for response control. The frontend communicates with the backend API to request AI-generated responses based on the provided prompts.

4. **Interactive User Interface**: The application provides a responsive and visually appealing user interface using Tailwind CSS and Shaden UI. Users can view generated AI completions, adjust parameters, and interact with videos seamlessly.

The frontend leverages modern web technologies, including WebAssembly, FFmpeg.js, Tailwind CSS, Radix UI, and Shaden UI, to deliver a powerful and engaging user experience. It eliminates the need for server-side video processing, simplifying the application's architecture while providing flexibility for customization and extension.
