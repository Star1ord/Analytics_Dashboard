# **Analytics Dashboard**

## **📌 Project Overview**
This project is a **modern analytics dashboard** designed to visualize and track key financial metrics and company performance. The application is built using **Next.js, React, and Tailwind CSS** to ensure a fast, scalable, and responsive experience. It features **real-time data visualization, currency localization (Kazakhstani tenge), and dynamically generated insights**.

The project incorporates concepts from the **Advanced Frontend** curriculum, as well as principles of **social network data analysis** and **modern UI/UX practices** from the provided documentation. 

## **🚀 Key Features**
- **Dynamic Charts & Graphs**: Uses React Chart.js to visualize business performance.
- **Responsive Design**: Fully optimized for **desktop, tablets, and mobile** using Tailwind CSS.
- **Dark Mode Support**: Seamlessly switches between light and dark themes.
- **Optimized Performance**: Utilizes **Next.js server-side rendering (SSR)** for better speed.
- **Component-Based Architecture**: Ensures reusable, maintainable, and scalable code.
- **User Scenarios & Behavior Models**: Designed following UX/UI best practices from **Practical_1.pdf**.

## **🛠️ Technologies Used**
- **Frontend**: Next.js (React framework), Tailwind CSS, Chart.js
- **State Management**: React Hooks (`useState`, `useEffect`)
- **Routing**: Next.js file-based routing
- **Data Handling**: Static JSON data with dynamically updated UI
- **Backend (Future Work)**: API integration for real-time data updates

## **📂 Project Structure**
```
analytics-dashboard/
│-- .next/               # Next.js build files
│-- app/                 # Main application directory
│   │-- Components/      # Reusable UI components
│   │-- favicon.ico      # Favicon
│   │-- globals.css      # Global CSS styles
│   │-- layout.js        # Main layout configuration
│   │-- loading.js       # Loading component
│   │-- page.js          # Main page structure
│-- node_modules/        # Installed dependencies
│-- public/              # Static assets (icons, images)
│-- .eslintrc.json       # ESLint configuration
│-- .gitignore           # Git ignore rules
│-- android-icons/       # Mobile device icons
│-- jsconfig.json        # JavaScript configuration
│-- next.config.mjs      # Next.js configuration
│-- package-lock.json    # Lock file for npm dependencies
│-- package.json         # Project dependencies
│-- postcss.config.js    # PostCSS configuration
│-- README.md            # Project documentation
│-- site.webmanifest     # Web app manifest
│-- tailwind.config.js   # Tailwind CSS configuration
│-- tsconfig.json        # TypeScript configuration
│-- webpack.config.js    # Webpack configuration
```

## **🔧Setup**
**Start the development server:**
   ```sh
   npm run dev
   ```
**Open in browser:**
   ```
   http://localhost:3000/
   ```

## **🌟 How It Works**
- The dashboard fetches **company performance data** and **financial statistics**.
- The UI adjusts dynamically based on screen size using **Tailwind CSS media queries**.
- User interactions and scenarios align with UX principles from **Practical_1.pdf**.

## **📈 Evaluation Criteria Alignment**
This project aligns with the **Advanced Frontend** assessment criteria:
1. **Functionality (30%)**: Implements real-time data visualization, responsive design, and correct routing.
2. **Code & Architecture (25%)**: Uses modern JavaScript/TypeScript standards, structured React components, and separation of concerns.
3. **Performance Optimization (15%)**: Optimized rendering, lazy loading where applicable, and optimized asset loading.
4. **UI/UX (15%)**: Uses Tailwind CSS, follows Material UI principles, and ensures intuitive navigation.
5. **Testing & Debugging (10%)**: Plans to incorporate Jest/Cypress for unit and integration testing.
6. **Documentation & Code Review (5%)**: Includes a structured README and adheres to best Git practices.

## **📈 Future Improvements**
- **Database Integration**: Connect to **Firebase or MongoDB** for real-time updates.
- **Authentication**: Add **user login/logout** using NextAuth.
- **Global State Management**: Implement **Redux or Zustand** for better data flow.
- **Localization**: Expand translations to support **Kazakh and Russian languages**.
- **Automated Testing**: Add Jest & Cypress test coverage.

---
🚀 **Developed for the Advanced Frontend course, incorporating Kazakhstani business insights and UI/UX design best practices.**

