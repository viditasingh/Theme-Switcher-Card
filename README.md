# React Theme Switcher

A modern React application that demonstrates theme switching functionality using React Context API and Tailwind CSS for styling.

## Features

- Light and dark theme toggle
- Context API for state management across components
- Responsive design with Tailwind CSS
- Profile card demo with dynamic styling based on theme

## Technologies Used

- React 19
- Tailwind CSS 4.1
- Vite 6.3
- Context API for state management

## Screenshots
![light theme](https://i.ibb.co/whRtkTZG/image.png)

![dark theme](https://i.ibb.co/k2hX9kr1/Screenshot-2025-05-13-014215.png)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/react-theme-switcher.git
```
```bash
cd react-theme-switcher
```

2. Install dependencies:
```bash
npm install 
```

3. Start the development server:
```bash
npm run dev 
```


## Project Structure

[📁 components](https://github.com/viditasingh/Theme-Switcher-Card/tree/main/src/components) - Contains UI components like Card and ThemeButton

[📁 contexts](https://github.com/viditasingh/Theme-Switcher-Card/tree/main/src/contexts) - Contains theme context for state management

[📁 assets](https://github.com/viditasingh/Theme-Switcher-Card/tree/main/src/assets) - Static assets like images

[📄 App.jsx](https://github.com/viditasingh/Theme-Switcher-Card/blob/main/src/App.jsx) - Main application component with theme provider setup

## How the Theme Switching Works
The application uses React's Context API to manage theme state across components. The theme can be toggled between light and dark modes using the toggle button, which updates the HTML document's class attribute to apply the appropriate styling.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is for educational purposes only