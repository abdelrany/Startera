# Startera

A modern React Native starter template built with Expo, TypeScript, and NativeWind. This is my personal starter template for building React Native applications.

## 🚀 Features

- **Expo SDK 53** with Custom Dev Client
- **TypeScript** for type safety
- **NativeWind** for styling with Tailwind CSS
- **Expo Router** for file-based navigation
- **React Query** with Axios for data fetching
- **Zustand** for state management
- **React Hook Form** with Zod validation
- **i18n** support with react-i18next
- **Jest** testing setup
- **Maestro** for E2E testing
- **GitHub Actions** for CI/CD

## 📱 Getting Started

### Prerequisites

- Node.js 18+
- pnpm
- Expo CLI
- iOS Simulator (for iOS development)
- Android Studio (for Android development)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/startera.git
cd startera
```

2. Install dependencies:

```bash
pnpm install
```

3. Start the development server:

```bash
pnpm start
```

4. Run on your preferred platform:

```bash
# iOS
pnpm ios

# Android
pnpm android
```

## 🏗️ Project Structure

```
src/
├── api/          # API related code
├── app/          # Expo Router screens
├── components/   # Shared components
├── lib/          # Utilities and hooks
├── translations/ # i18n files
└── types/        # TypeScript types
```

## 🔧 Environment Configuration

The project supports multiple environments (development, staging, production). Configure your environment variables in the respective `.env` files.

## 📚 Available Scripts

- `pnpm start` - Start Expo development server
- `pnpm ios` - Run on iOS simulator
- `pnpm android` - Run on Android emulator
- `pnpm test` - Run tests
- `pnpm lint` - Run ESLint
- `pnpm type-check` - Run TypeScript type checking

## 🧪 Testing

- **Unit Tests**: Jest + React Native Testing Library
- **E2E Tests**: Maestro
- **Linting**: ESLint with Expo config

## 📦 Building

### Development Build

```bash
pnpm prebuild:development
```

### Staging Build

```bash
pnpm prebuild:staging
```

### Production Build

```bash
pnpm prebuild:production
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

Built with ❤️ using modern React Native best practices.
