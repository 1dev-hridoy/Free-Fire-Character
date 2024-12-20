# Free-Fire-Character API

![Free Fire Character](https://raw.githubusercontent.com/1dev-hridoy/Free-Fire-Character/refs/heads/main/assets/standard.gif)

This project is a web application that allows users to explore characters from the popular game Free Fire. It provides a visually appealing interface to browse, search, and view detailed information about various Free Fire characters.

## Features

- Browse a grid of Free Fire characters
- Search for specific characters
- View detailed information about each character
- Responsive design for mobile and desktop
- Dark theme with animated UI elements

## Technologies Used

- Node.js
- Express.js
- HTML5
- CSS3 (with Tailwind CSS)
- JavaScript (ES6+)
- Nexalo API for Free Fire character data

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm (comes with Node.js)
- A Nexalo API key (instructions below)

### Obtaining the API Key

To use this application, you'll need to obtain an API key from Nexalo. Follow these steps:

1. Go to [https://nexalo.xyz/user/auth/signup](https://nexalo.xyz/user/auth/signup) and sign up for an account.
2. After signing up and logging in, navigate to your profile page.
3. Look for the API key section. You should see your API key displayed there.
4. Copy this API key; you'll need it to set up the application.

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/1dev-hridoy/Free-Fire-Character.git
   ```

2. Navigate to the project directory:
   ```
   cd free-fire-character
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add your Nexalo API key:
   ```
   API_KEY=your_api_key_here
   ```

5. Start the server:
   ```
   npm start
   ```

6. Open your browser and visit `http://localhost:3000` (or whatever port you've configured).

## Usage

- The main page displays a grid of Free Fire characters.
- Use the search bar at the top to find specific characters.
- Click on a character card to view more detailed information about that character.
- The interface is responsive and works on both desktop and mobile devices.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to Nexalo for providing the Free Fire character data API.
- This project uses Tailwind CSS for styling.

## Support

If you encounter any issues or have questions, please open an issue in this repository or contact the maintainer.

Enjoy exploring Free Fire characters!
