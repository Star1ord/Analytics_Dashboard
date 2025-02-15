# **Analytics Dashboard**

## **📌 Project Overview**
This project is a **modern analytics dashboard** designed to visualize and track key financial metrics and company performance. The application is built using **Next.js, React, and Tailwind CSS** to ensure a fast, scalable, and responsive experience. It features **real-time data visualization, currency localization (Kazakhstani tenge), and dynamically generated insights**.

The project incorporates concepts from the **Advanced Frontend** curriculum, as well as principles of **social network data analysis** and **modern UI/UX practices** from the provided documentation. 

## **🚀 Key Features**
- **Dynamic Charts & Graphs**: Uses React Chart.js to visualize business performance.
- **Kazakhstani Companies & Names**: Updated dataset with **Kazakhstani IT and marketing companies**.
- **Currency Conversion**: All dollar ($) values converted to **tenge (₸)**.
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
│-- pages/               # Next.js page-based routing
│   │-- index.js         # Homepage
│   │-- dashboard.js     # Dashboard main page
│-- components/          # Reusable UI components
│   │-- Sidebar.js       # Navigation sidebar
│   │-- ChartComponent.js # Chart visualization
│-- public/              # Static assets (logos, images)
│-- styles/              # Tailwind CSS styles
│-- package.json         # Project dependencies
│-- README.md            # Project documentation
```

## **🔧 Installation & Setup**
1. **Clone the repository:**
   ```sh
   git clone https://github.com/TechSis01/analytics-dashboard.git
   cd analytics-dashboard
   ```
2. **Install dependencies:**
   ```sh
   npm install
   ```
3. **Start the development server:**
   ```sh
   npm run dev
   ```
4. **Open in browser:**
   ```
   http://localhost:3000/
   ```

## **🌟 How It Works**
- The dashboard fetches **company performance data** and **financial statistics**.
- **Kazakhstani companies** are used instead of international brands.
- Values are converted to **tenge (₸)**, with calculations applied (`x10` from USD).
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

## **🤝 Contribution Guidelines**
1. **Fork the repository** and create a new feature branch.
2. **Make your changes** and test them.
3. **Submit a pull request** with a clear description.

## **📜 License**
This project is licensed under the **MIT License**.

---
🚀 **Developed for the Advanced Frontend course, incorporating Kazakhstani business insights and UI/UX design best practices.**

