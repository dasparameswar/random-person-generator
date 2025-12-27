# 👤 Random Person Generator

> Generate realistic fake person profiles for testing and development - Built with React

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

## 🌟 Features

- 👤 **Random Profiles** - Generate complete person profiles instantly
- 🖼️ **Profile Pictures** - Random avatars included
- 📧 **Contact Info** - Email, phone, and address
- 🌍 **Multiple Locales** - Support for different countries/regions
- 📋 **Copy to Clipboard** - Easy data copying
- 🎲 **Customizable** - Choose specific data fields
- 💾 **Export Options** - JSON, CSV, or plain text
- ⚡ **Fast React UI** - Smooth, responsive interface

## 🚀 Live Demo

🔗 **[Try it here](https://dasparameswar.github.io/random-person-generator/)**

## 📸 Preview

> **Note:** Add screenshots! Create `screenshots/` folder and add:
> - `screenshots/main.png` - Main interface with generated profile
> - Demo GIF showing profile generation

## 🛠 Tech Stack

- **Framework:** React.js
- **Language:** JavaScript
- **Styling:** Tailwind CSS
- **API:** Random User API (randomuser.me)
- **Build Tool:** Create React App

## 💡 Use Cases

Perfect for:

- 🧪 **Testing** - Populate test databases with realistic data
- 🎨 **UI Mockups** - Create realistic design prototypes
- 📚 **Development** - Generate sample data for applications
- 🎓 **Learning** - Practice React and API integration
- 🔍 **QA Testing** - Test forms and user flows
- 📊 **Data Visualization** - Mock data for charts and dashboards

## 💻 Getting Started

### Prerequisites

- Node.js 14+ installed
- npm or yarn package manager

### Installation

```bash
# Clone repository
git clone https://github.com/dasparameswar/random-person-generator.git
cd random-person-generator

# Install dependencies
npm install

# Start development server
npm start
```

Visit `http://localhost:3000` in your browser

### Building for Production

```bash
# Create production build
npm run build

# Deploy the build folder
```

## 📁 Project Structure

```
random-person-generator/
├── public/             # Static files
├── src/
│   ├── components/     # React components
│   ├── services/       # API service
│   ├── App.js          # Main component
│   └── index.js        # Entry point
├── tailwind.config.js  # Tailwind configuration
├── package.json        # Dependencies
└── README.md           # Documentation
```

## 🎯 Generated Data Fields

Each generated person includes:

### Personal Info
- Full name (first, middle, last)
- Gender
- Date of birth
- Age
- Nationality

### Contact Details
- Email address
- Phone number
- Cell phone

### Location
- Street address
- City
- State/Province
- Country
- Postal code

### Visual
- Profile picture (thumbnail, medium, large)
- Random avatar

## 📋 Usage Examples

### Generate Single Person

1. Open the app
2. Click "Generate Person"
3. View the generated profile

### Copy Data

- Click individual copy buttons for specific fields
- Copy entire profile as JSON
- Export multiple profiles at once

### Customize Generation

- Select gender preference
- Choose nationality
- Pick specific data fields

## 🌐 API Integration

This app uses the [Random User API](https://randomuser.me/):

```javascript
// Example API call
fetch('https://randomuser.me/api/')
  .then(response => response.json())
  .then(data => console.log(data.results[0]))
```

### API Parameters

```
https://randomuser.me/api/?gender=male&nat=us&results=5
```

- `gender` - male, female, or random
- `nat` - nationality (us, gb, fr, etc.)
- `results` - number of profiles to generate

## 🧪 Available Scripts

### `npm start`
Runs the app in development mode

### `npm test`
Launches the test runner

### `npm run build`
Builds the app for production

## 🎨 Styling

This project uses **Tailwind CSS** for styling:

- Responsive utility classes
- Custom color scheme
- Dark mode support (optional)
- Modern, clean design

## 🗺️ Future Enhancements

- [ ] Bulk generation (10, 50, 100+ profiles)
- [ ] Advanced filtering options
- [ ] Save favorite profiles
- [ ] History of generated profiles
- [ ] Custom API endpoint support
- [ ] Database export functionality
- [ ] PDF report generation
- [ ] More data fields (job, company, bio)
- [ ] Dark mode toggle

## 🤝 Contributing

Contributions are welcome!

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is [MIT](LICENSE) licensed.

## 👤 Author

**Parameswar Das**

- GitHub: [@dasparameswar](https://github.com/dasparameswar)
- LinkedIn: [dasparameswar](https://linkedin.com/in/dasparameswar)
- Email: parameswar.das@tiqo.co

## 🙏 Acknowledgments

- [Random User API](https://randomuser.me/) - For providing the fake user data
- [Tailwind CSS](https://tailwindcss.com/) - For beautiful styling utilities
- React community - For amazing framework and ecosystem

---

⭐ Star this repository if it helps your development workflow!

---

*Built with React & Tailwind CSS by Parameswar Das* 💻
