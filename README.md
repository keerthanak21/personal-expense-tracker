# 💰 Expense Tracker Mobile App

A modern, cross-platform personal finance mobile application built with React Native and Expo for tracking daily expenses with intuitive category management and comprehensive spending analytics.

## 🚀 Features

### Core Functionality
- ✅ **Add Expenses** - Quick expense entry with amount, description, category, and date
- ✅ **Expense Management** - View, edit, and delete recorded expenses
- ✅ **Category Organization** - Pre-defined categories with custom icons and colors
- ✅ **Smart Analytics** - Monthly and total spending statistics
- ✅ **Dashboard Overview** - Real-time spending insights and recent transactions

### User Experience
- 📱 **Cross-Platform** - Works on Android, iOS, and Web
- 🎨 **Modern UI** - Clean, intuitive interface with Material Design
- 💾 **Offline Storage** - Local data persistence using AsyncStorage
- 📊 **Visual Analytics** - Category-wise spending breakdown with progress bars
- 🗓️ **Date Management** - Easy date selection with native date picker

### Technical Features
- ⚡ **Real-time Updates** - Instant data synchronization across screens
- 🔄 **State Management** - Efficient React Context API implementation
- 📱 **Responsive Design** - Optimized for different screen sizes
- 🛡️ **Type Safety** - Full TypeScript implementation
- 🎯 **Performance** - Optimized rendering and smooth animations

## 🛠️ Technologies Used

| Category | Technologies |
|----------|-------------|
| **Frontend** | React Native, TypeScript, JavaScript |
| **Framework** | Expo SDK 53 |
| **Navigation** | Expo Router (File-based routing) |
| **Storage** | AsyncStorage (SharedPreferences equivalent) |
| **UI Library** | React Native Paper, Expo Vector Icons |
| **State Management** | React Context API, Custom Hooks |
| **Development** | Metro Bundler, TypeScript Compiler |
| **Platform Support** | Android, iOS, Web |

## 📦 Installation & Setup

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- Expo CLI
- Android Studio (for Android development)
- Xcode (for iOS development - macOS only)

### Quick Start

1. **Clone the repository**
```bash
git clone <repository-url>
cd expense-tracker
```

2. **Install dependencies**
```bash
npm install
# or
yarn install
```

3. **Start the development server**
```bash
npx expo start
```

4. **Run on your preferred platform**
- **Android**: Press `a` or scan QR code with Expo Go app
- **iOS**: Press `i` or scan QR code with Camera app
- **Web**: Press `w` or visit `http://localhost:8081`

### Development Commands

```bash
# Start development server
npm start

# Run on Android emulator
npm run android

# Run on iOS simulator
npm run ios

# Run on web browser
npm run web

# Type checking
npm run type-check

# Build for production
npx expo build
```

## 🎯 Usage

### Adding an Expense
1. Navigate to the **Add Expense** tab
2. Enter the expense amount
3. Add a description
4. Select a category
5. Choose the date (defaults to today)
6. Tap **Add Expense**

### Viewing Expenses
- **Dashboard**: See recent expenses and monthly summary
- **Expenses Tab**: View all expenses with delete functionality
- **Statistics**: Analyze spending by category with visual breakdowns

### Managing Categories
The app includes 8 pre-defined categories:
- 🍽️ Food & Dining
- 🚗 Transportation
- 🛒 Shopping
- 🎬 Entertainment
- 📄 Bills & Utilities
- 🏥 Healthcare
- 🎓 Education
- ➕ Other

## 📊 Key Features Breakdown

### Dashboard Screen
- Monthly spending overview
- Total expenses summary
- Recent transactions list
- Quick stats cards

### Add Expense Screen
- Form validation
- Category selector with icons
- Date picker integration
- Success/error handling

### Expenses List Screen
- All expenses chronologically
- Delete functionality
- Category visual indicators
- Empty state handling

### Statistics Screen
- Category-wise spending breakdown
- Percentage calculations
- Visual progress indicators
- Sorted by spending amount


screenshots:
![WhatsApp Image 2025-08-03 at 00 57 45](https://github.com/user-attachments/assets/4ee93e71-011e-4aa0-ba79-08e09ace9e26)
![WhatsApp Image 2025-08-03 at 00 57 44](https://github.com/user-attachments/assets/4822f1c4-89d9-4699-86d3-28e276cda376)
![WhatsApp Image 2025-08-03 at 00 57 44 (2)](https://github.com/user-attachments/assets/59628cc2-7e8e-4e8c-a034-3b181e45cce6)
![WhatsApp Image 2025-08-03 at 00 57 44 (1)](https://github.com/user-attachments/assets/3e899f61-b4b3-4fcf-aa91-40ae6cbee8b7)
