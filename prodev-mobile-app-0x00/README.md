# 1. Create Your First Mobile App

## Objective
Set up a first mobile application using the **Expo Router template** and document the scaffolding process. Understand the file structure of a React Native application using Expo.

---

## Steps for Scaffolding

1. **Navigate to the project directory**  
```bash
cd prodev-mobile-setup
````

2. **Initialize a new Expo project** using the latest Expo Router template:

```bash
npx create-expo-app@latest .
```

3. **Modify the Home Screen**

* Open `app/(tabs)/index.tsx`
* Locate the default text `Welcome!`
* Change it to:

```tsx
<Text>First App Created</Text>
```

4. **Run and Test the Application**

```bash
npx expo start
```

* **iOS Devices:** Scan the QR code in the terminal using the Camera app
* **Android Devices:** Scan the QR code using Expo Go

---

## Resetting the Project

Run the reset command:

```bash
npm run reset-project
```

**Observation:**

* The command removes generated caches and temporary files
* Restores the project to a clean initial state without affecting the source code
* Helps fix issues caused by corrupted dependencies or builds

---

## Outcome

* Successfully created a React Native project using the Expo Router template
* Modified the home screen to display `First App Created`
* Tested the app on a physical device using Expo Go
* Learned the effects of resetting the project with `npm run reset-project`

---

## Repository Info

* **GitHub Repository:** `prodev-mobile-setup`
* **Directory:** `mobile-development-app-0x00`
* **Files:**

  * `README.md`
  * `app-example/app/(tabs)/index.tsx`
  * `app-example/constants/Colors.tsx`
  * `app-example`
