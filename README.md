# Collatz Conjecture Visualizer 📊

An interactive web visualization of the Collatz conjecture (also known as the 3n + 1 problem), built with pure HTML, JavaScript, and Chart.js. This tool allows users to explore different starting numbers and observe how the sequence evolves.

## 🔍 What is the Collatz Conjecture?

The Collatz conjecture is one of the most famous unsolved problems in mathematics. The rules are simple:

1. Start with any positive integer n
2. If n is even, divide it by 2
3. If n is odd, multiply it by 3 and add 1
4. Repeat steps 2-3 until you reach 1

The conjecture states that this sequence will eventually reach 1 for any starting positive integer.

## 🚀 Features

- **Interactive Input**: Enter any positive integer to see its Collatz sequence
- **Real-time Visualization**: Dynamic line graph showing the sequence evolution
- **Key Statistics**: 
  - Number of steps to reach 1
  - Highest value in the sequence
- **Full Sequence Display**: See the complete number sequence
- **Responsive Design**: Works on both desktop and mobile devices

## 🛠️ Installation

1. Clone this repository:
2. Open `collatz-visualization.html` in your web browser

That's it! No build process or dependencies to install locally.

## 💻 Usage

1. Open the webpage
2. Enter any positive integer in the input field
3. Click "Calculate" or press Enter
4. Observe the generated graph and statistics
5. Try different numbers to compare sequences

## 📈 Interesting Numbers to Try

- **27**: Demonstrates how numbers can grow very large before eventually reaching 1
- **19**: Takes many steps to reach 1
- **Powers of 2** (2, 4, 8, 16, etc.): Show the simplest possible sequences
- **Number with many steps**: 97, 871, 6171

## 🔧 Technical Details

### Dependencies
- Chart.js v3.7.0 (loaded via CDN)

### Browser Support
- Works in all modern browsers (Chrome, Firefox, Safari, Edge)
- Requires JavaScript enabled

## 🤝 Contributing

Contributions are welcome! Here are some ways you can contribute:

1. Report bugs
2. Suggest new features
3. Submit pull requests
4. Improve documentation

Please ensure your pull requests are well-documented.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- Thanks to Lothar Collatz for formulating this fascinating conjecture
- Chart.js team for the excellent graphing library

## 📧 Contact

If you have any questions or suggestions, please open an issue on GitHub.
