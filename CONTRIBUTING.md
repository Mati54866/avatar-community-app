# Contributing to Avatar Community App 📱

Thank you for contributing to **Avatar Community App**! This React Native (Expo) app delivers dynamic social and avatar features.

---

## 🛠️ Expo Development Environment

1. **Install Expo CLI globally**:
   ```bash
   npm install -g expo-cli
   ```

2. **Clone & Install**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/avatar-community-app.git
   cd avatar-community-app
   npm install
   ```

3. **Run Dev Server**:
   ```bash
   npx expo start
   ```

---

## 📱 Component Architecture Standards

- Store reusable UI components in `components/`.
- Use custom hooks (`hooks/`) for complex business logic and state management.
- Utilize React Query (TanStack Query) for server state caching and optimistic UI updates.
