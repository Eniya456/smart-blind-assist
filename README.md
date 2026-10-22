# Smart Blind Assist 👁️

### AI-Powered Accessibility Web Application for Visually Impaired Individuals

## 📌 About the Project

**Smart Blind Assist** is a web-based assistive technology application designed to support visually impaired individuals in their daily lives. It combines web technologies and AI-based capabilities to help users understand their surroundings and access assistance through a user-friendly interface.

The application is built using React and TypeScript, with Supabase integration and TensorFlow.js libraries for machine-learning capabilities.

## 🎯 Objectives

- Improve accessibility for visually impaired individuals.
- Support environmental awareness through camera-based AI capabilities.
- Provide a user-friendly interface for accessing assistance.
- Explore digital tools that promote independent living.
- Develop a scalable software solution focused on inclusive technology.

## ✨ Key Features

- **AI-Based Object Detection:** Integrates TensorFlow.js and the COCO-SSD model for potential camera-based object recognition.
- **Webcam Integration:** Uses webcam capabilities to provide camera input.
- **User Authentication:** Includes Supabase integration for authentication-related functionality.
- **Role-Based Interface:** Includes user and caregiver dashboard components.
- **Interactive Maps:** Uses Leaflet and React Leaflet for map-based functionality.
- **Responsive User Interface:** Built with React and styled for an accessible, interactive experience.

*Note: The features listed should match the functionality implemented in the current version of the application.*

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Frontend | React, TypeScript |
| Build Tool | Vite |
| AI / Machine Learning | TensorFlow.js, COCO-SSD |
| Backend Services | Supabase |
| Mapping | Leaflet, React Leaflet |
| UI and Animations | Lucide React, Framer Motion |
| Webcam | React Webcam |
| Code Quality | ESLint |

## 🏗️ System Architecture

The application follows a component-based web architecture.

1. **User Interface:** React components provide the screens and interactive elements.
2. **Camera Input:** Webcam integration provides visual input where required.
3. **AI Processing:** TensorFlow.js and COCO-SSD support object detection capabilities.
4. **Authentication and Data Services:** Supabase provides backend services for supported authentication and data operations.
5. **Navigation and Mapping:** React Router manages application navigation, while Leaflet supports map-based features.

## ⚙️ Installation and Setup

### Prerequisites

- Node.js and npm
- Git
- A modern web browser
- A webcam for camera-dependent features
- Supabase project credentials, if required by the application

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Smart-Blind-Assist.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Smart-Blind-Assist
```

### Step 3: Install Dependencies

```bash
npm install
```

### Step 4: Configure Environment Variables

Create a `.env` file in the project root and configure the Supabase credentials required by the application.

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_publishable_or_anon_key
```

Use the correct key format supported by your Supabase project. Never commit your `.env` file or any secret service-role keys to GitHub.

### Step 5: Start the Development Server

```bash
npm run dev
```

Open the local URL displayed in your terminal to access the application.

### Step 6: Build for Production

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## 📂 Project Structure

```text
Smart-Blind-Assist/
├── public/                  # Static assets
├── src/
│   ├── hooks/               # Reusable React hooks
│   ├── pages/               # Application pages and dashboards
│   ├── components/          # Reusable UI components
│   ├── main.tsx             # Application entry point
│   └── ...                  # Other application modules
├── index.html               # HTML entry point
├── package.json             # Dependencies and scripts
├── eslint.config.js         # ESLint configuration
├── .gitignore               # Ignored files
└── README.md                # Project documentation
```

*The directory structure above is illustrative; adjust it to reflect the complete repository.*

## 🌍 Use Cases

- Assistive web applications for visually impaired users.
- Camera-based object recognition and environmental awareness.
- Digital support interfaces for users and caregivers.
- Accessibility-focused software development and research.

## 🔮 Future Enhancements

- Integrate voice-based feedback and text-to-speech support.
- Improve real-time object detection and spoken object descriptions.
- Add more accessible keyboard navigation and screen-reader support.
- Enhance obstacle awareness and navigation assistance.
- Expand caregiver support and emergency assistance features.
- Improve testing, performance, and accessibility compliance.

## ⚠️ Safety Disclaimer

Smart Blind Assist is intended to provide supplementary digital assistance. AI predictions may be inaccurate, and the application should not replace a white cane, guide dog, mobility training, or other established safety measures.

## 🤝 Contributing

Contributions and suggestions are welcome.

1. Fork this repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request with a description of your improvements.

## 👩‍💻 Author

**Eniya V**


---

**Smart Blind Assist — Leveraging AI and web technology to build a more accessible world.**
