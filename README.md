# ALX Listing App

## 📝 Project Description
This project is an **Airbnb clone listing page** built with **Next.js** using the **Pages Router**, **TypeScript** for type safety, and **Tailwind CSS** for responsive styling. The primary goal is to create a well-structured, maintainable codebase that will serve as the foundation for a full-featured property listing application.

## 📂 Project Structure
The project follows a modular structure to ensure maintainability:

* **`components/`**: Contains all reusable UI components.
    * **`common/`**: Stores highly reusable, low-level components like **`Card.tsx`** and **`Button.tsx`**.
* **`pages/`**: The core directory for page components, following the Pages Router conventions.
* **`interfaces/`**: Holds all TypeScript type definitions and interfaces (e.g., **`CardProps`**, **`Listing`**) in **`index.ts`**.
* **`constants/`**: Stores global data, configuration settings, and static text in **`index.ts`**.
* **`public/`**: Assets served directly.
    * **`assets/`**: Contains images, SVGs, and other media used throughout the application.

## 🚀 Getting Started

### **Prerequisites**
* Node.js (LTS recommended)
* npm or yarn

### **Installation**
1.  Clone the repository (if applicable) and navigate to the project directory:
    ```bash
    cd alx-listing-app
    ```
2.  Install the necessary dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```

### **Running the Development Server**
Start the development server:

```bash
npm run dev
# or
yarn dev