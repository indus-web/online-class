
# Online Class Platform

Welcome to the Online Class Platform project! This open-source project is designed to provide a comprehensive solution for online education, featuring a collaborative whiteboard, video call functionality, and screen presentation tools. Our goal is to help educators and students engage more effectively through a seamless and interactive online learning experience.

## Features
- Collaborative Whiteboard: Interactive whiteboard for drawing, writing, and sharing ideas - in real-time.
- Video Call: High-quality video conferencing for live lectures and discussions.
Screen Presentation: Share your screen to present slides, documents, and other materials.

## Getting Started

### Prerequisites
- Node.js (v14 or later)
- npm or Yarn
- A modern web browser (Chrome, Firefox, etc.)


## Installation
### 1. Clone the Repository

```bash
 git clone https://github.com/your-username/online-class-platform.git
 cd online-class-platform

```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
```
### 3. Run the Development Server

```bash
npm start
# or
yarn start

```

The application will be available at http://localhost:3000.

## Configuration

Create a .env file in the root directory and add the following environment variables:

```bash
REACT_APP_API_URL=http://localhost:5000
REACT_APP_WEBCAM_PERMISSION=true

```
Adjust the values according to your configuration.

## Usage

### Whiteboard
- Access the whiteboard from the main dashboard.
- Use the toolbar to draw, write, and interact with the board.
- Collaborate with others in real-time.

### Video Call
- Start or join a video call from the "Calls" tab.
- Use the built-in chat feature to communicate during calls.
- Share your screen using the screen share option.


### Screen Presentation
- Access the presentation tool from the main dashboard.
- Upload and present documents or slides.
- Use the annotation tools to highlight key points.

## Integration


If you want to integrate the Online Class Platform into your own project, you can use our package:

### 1. Install the Package

```bash
npm install online-class-platform
# or
yarn add online-class-platform

```

### 2. Import and Use

```bash
import { Whiteboard, VideoCall, ScreenPresentation } from 'online-class-platform';

function App() {
  return (
    <div>
      <Whiteboard />
      <VideoCall />
      <ScreenPresentation />
    </div>
  );
}

```
Follow our integration guide for more details.



## Contributing
We welcome contributions to improve the Online Class Platform. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature).
3. Commit your changes (git commit -am 'Add new feature').
4. Push to the branch (git push origin feature/your-feature).
5. Create a new Pull Request.

Please review our contributing guidelines before submitting a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
For any questions or feedback, please open an issue on GitHub or contact us at support@example.com.
