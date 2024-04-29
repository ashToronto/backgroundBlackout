# Background Blackout

Background Blackout is a Next.js application designed to accurately remove backgrounds from uploaded images. The app integrates machine learning capabilities via the [Replicate API](https://replicate.com/) for image manipulation and uses Stripe for payment processing.

## Features

- **Image Background Removal**: Upload images and remove backgrounds with high accuracy.
- **Stripe Integration**: Secure payment processing for premium features.

## Technologies

- **Next.js 14.2.3**: The React framework for production.
- **React 18**: A JavaScript library for building user interfaces.
- **TypeScript**: Adds static types to JavaScript for better code quality and developer experience.
- **Node.js 20.12.1**: A JavaScript runtime built on Chrome's V8 JavaScript engine.
- **TailwindCSS**: A utility-first CSS framework for rapid UI development.
- **React Dropzone**: Drag-and-drop file upload area ([React Dropzone](https://react-dropzone.js.org)).
- **React Icons**: Include popular icons in your React projects ([React Icons](https://react-icons.github.io/react-icons)).
- **Artifical Intelligence**: Image removal model run by ([replicate](https://replicate.com/cjwbw/rembg)).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Ensure you have Node.js version 20.12.1 installed. You can manage multiple versions of Node.js with a version manager such as [nvm](https://github.com/nvm-sh/nvm).

- You will need a replicate api token setup .env.local and add `REPLICATE_API_TOKEN = YOUR_REPLICATE_API_KEY;`

- Replicate is free till credits run out. Check pricing of the models and hardware [replicate](https://replicate.com/pricing).

- Remember each model has different versions, which you can check on the "Versions" tab.

- Check the [replicate predictions tab](https://replicate.com/predictions) to see the status of each run and how long it took to generate the modified image.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/background_blackout.git
   ```

### Getting Started

First, run the development server:

```bash
npm run dev

```
