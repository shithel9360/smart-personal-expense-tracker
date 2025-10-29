# Smart Personal Expense Tracker

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![React](https://img.shields.io/badge/react-18.x-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Project Overview
Smart Personal Expense Tracker is an AI-powered financial management application that automatically categorizes expenses, provides budget forecasting, and delivers personalized financial insights. Track your spending habits, set budgets, and achieve your financial goals with intelligent recommendations.

## Tech Stack
- **Frontend**: React.js, Redux Toolkit, Chart.js, Material-UI
- **Backend**: Node.js, Express.js
- **AI/ML**: TensorFlow.js, Python (Flask microservice)
- **Database**: MongoDB, PostgreSQL
- **Authentication**: JWT, OAuth 2.0
- **Payment Integration**: Plaid API, Stripe
- **Analytics**: Google Analytics, Mixpanel
- **Testing**: Jest, Cypress, Mocha

## Features
- ✅ AI-powered expense categorization
- ✅ Budget creation and tracking
- ✅ Income vs expense visualization
- ✅ Predictive spending analytics
- ✅ Bill reminders and notifications
- ✅ Multi-currency support
- ✅ Receipt scanning with OCR
- ✅ Financial goal setting and tracking
- ✅ Expense reports and exports (PDF/CSV)
- ✅ Bank account integration
- ✅ Recurring expense detection
- ✅ Custom categories and tags

## Setup Instructions

### Prerequisites
- Node.js 14.x or higher
- Python 3.8+ (for AI microservice)
- MongoDB
- PostgreSQL

### Installation

```bash
# Clone the repository
git clone https://github.com/shithel9360/smart-personal-expense-tracker.git
cd smart-personal-expense-tracker

# Install dependencies
npm install

# Set up AI microservice
cd ai-service
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your API keys and database URLs

# Run database migrations
npm run migrate

# Start the backend
npm run server

# In a new terminal, start AI service
cd ai-service
python app.py

# In another terminal, start frontend
npm start
```

### Running Tests

```bash
# Run all tests
npm test

# Run backend tests
npm run test:backend

# Run frontend tests
npm run test:frontend

# Run E2E tests
npm run test:e2e
```

## Demo

![Demo GIF Placeholder](https://via.placeholder.com/800x400.png?text=Expense+Tracker+Demo)

## API Documentation

API documentation available at `/api/docs` when server is running.

## Contributing

Contributions welcome! Please read CONTRIBUTING.md first.

## License

MIT License - see LICENSE file for details

## Contact

Shithel - [@shithel9360](https://github.com/shithel9360)
