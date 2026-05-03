# Udaan - Disability Bridge

A comprehensive platform bridging disabilities through accessible employment opportunities, community support, and innovative technology integration.

## Project Overview

This monorepo contains three main components:

### Frontend
- **Framework**: Vite + React with TypeScript
- **Key Features**:
  - Accessibility toolbar with WCAG compliance
  - Real-time speech recognition and captions
  - ISL (Indian Sign Language) panel support
  - Floating accessibility widget
  - Braille text support
  - Voice router for hands-free navigation

### Backend
- **Stack**: Node.js + Express
- **Services**:
  - ML pipeline integration (TensorFlow Lite models)
  - MediaPipe extractor for gesture recognition
  - Sentence recognizer for ASL/ISL
  - Schema engine for dynamic form management
  - WhatsApp integration via Twilio
  - PostgreSQL database with migrations

### Blockchain
- **Platform**: Hardhat (Ethereum)
- **Smart Contracts**: UDID Registry for decentralized identity

## Key Features

- 🎯 **Accessibility First**: Built with comprehensive accessibility standards
- 🔐 **Blockchain Identity**: Decentralized UDID (Universal Disability Identity) management
- 🗣️ **Multi-modal Communication**: Voice, text, ASL, ISL, Braille support
- 🤖 **ML-Powered**: Real-time gesture and speech recognition
- 💼 **Employment Bridge**: Employer and candidate matching platform
- 🗺️ **Community Maps**: Location-based community resource discovery
- 📱 **Mobile Optimized**: Responsive design for all devices

## Getting Started

### Prerequisites
- Node.js 18+
- Python 3.9+
- PostgreSQL
- Hardhat for blockchain development

### Installation

```bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
pip install -r requirements.txt

# Setup blockchain
cd ../blockchain
npm install
```

### Running the Application

```bash
# Development server
cd frontend
npm run dev

# Backend API
cd backend
npm start

# ML services
python ml_service.py
```

## Project Structure

```
bridging-disabilities/
├── frontend/          # React + Vite application
├── backend/          # Node.js API server
│   ├── routes/       # API endpoints
│   ├── services/     # Business logic
│   ├── ml_service.py # ML pipeline
│   └── db.js         # Database configuration
├── blockchain/       # Smart contracts
└── README.md         # This file
```

## Recent Updates

- Integrated bridging-disabilities submodule updates
- Enhanced accessibility components and ML pipeline
- Improved voice routing and caption functionality
- Optimized MediaPipe extractor and schema engine
- Consolidated documentation

## Contributing

1. Create a feature branch
2. Make your changes
3. Test thoroughly
4. Submit a pull request

## License

MIT

## Support

For accessibility issues or feature requests, please open an issue in the repository.
