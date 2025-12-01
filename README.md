**Pizza User**

Pizza User is a cross-platform pizza ordering system with Web (React + Ant Design) and Mobile (React Native + TypeScript) applications. It allows users to browse menus, manage shopping carts, view order history, and complete orders across multiple stores. The application emphasizes a modular architecture, type safety, and responsive design.

**Features**
1. Core Functionality
- Menu Browsing: Display pizza items with name, description, price, stock, and images. Supports sorting and searching.
- Shopping Cart: Add or remove items, manage quantities, view cart grouped by store, automatic price calculation.
- Order Management: View order history, check order details, manage order status.
- User Profile: Manage personal information (basic framework).
- Multi-store Support: Supports multiple stores, with cart grouped by store.

2. Technical Features
- Cross-platform: Web application built with React and Ant Design; Mobile application built with React Native and TypeScript.
- Navigation: React Router for Web, React Navigation for Mobile.
- UI Components: Modular and reusable components for menus, headers, modals, and navigation.
- Data Transformation Layer: Unified handling of server responses and mock data.
- Type Safety: TypeScript ensures consistent types across the mobile app.
- State Management: Component state management using React hooks.
- HTTP Requests: Axios wrapper for network requests, with mock data support for development.

**Project Structure**

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/0dbfdaa2-02d2-4e16-ace4-53de942f87e6" />

**Installation**
1. Prerequisites
Node.js v12.x or higher
npm v6.x or higher (or yarn)
Mobile development: Xcode 11+ for iOS, Android Studio for Android

2. Web Application
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/6b84222e-e461-45c3-9170-4e1984b8ada9" />

Open http://localhost:3000
 to view the app.

3. Mobile Application
<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/74565dfb-e2b1-4efc-926f-332e4f4db1e4" />

**Application Pages**
- Home Page / Menu Page: Browse menu items, add/remove items to cart, sort and search, view store information.
- Shopping Cart Page: View cart items grouped by store, automatic price calculation, checkout, remove cart.
- Order Page: View order history, check order details, view status, delete orders.
- My Page: Display user profile information (basic framework).

**Components and Utilities**
- TopHeader / BottomBar: Navigation components.
- MenuItem / CartModal / ShopModal: Reusable UI components.
- Data Models: MenuItemDataType, cartSetItemType.
- Utilities: Price calculation, data transformation, HTTP request wrapper.

**Data Flow**
1. Fetch data from API or mock data.
2. Transform server data to application format.
3. Manage component state with React hooks.
4. Render UI components.
5. Handle user interactions (add to cart, checkout, etc.).

**Development Notes**
- Mobile app uses TypeScript for type safety.
- Web app uses JavaScript (ES6+).
- Both apps share component structures and modular design.
- Mock data used for development; switch to real API by updating service files.

**Known Issues / TODO**
- Complete search functionality.
- Enhance order details page.
- Complete user profile page.
- Integrate with real backend API.
- Add authentication, authorization, and payment integration.
- Improve error handling, loading states, and performance.
- Add unit and integration tests.

**Contributing**
- Fork the repository.
- Create a feature branch: git checkout -b feature/YourFeature.
- Commit changes: git commit -m "Add some feature".
- Push to branch: git push origin feature/YourFeature.
- Open a pull request.

**License**
This project is for educational purposes.
