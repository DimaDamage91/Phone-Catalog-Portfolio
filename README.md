# Apple Gadgets Store

Apple Gadgets Catalog is an online store where users can explore products across three categories: phones, tablets, and accessories (such as Apple Watch).
Users can browse the catalog using sorting and filtering options, view detailed product pages, and select different available characteristics.
Products can be added to favorites and to the shopping cart for further purchase.
The home page features multiple sliders showcasing highlighted products and the latest arrivals.

## Live Demo

🔗 Live website: [LIVE DEMO](https://dimadamage91.github.io/Phone-Catalog-Portfolio/)

🎨 Figma design: [LIVE DEMO](https://www.figma.com/design/T5ttF21UnT6RRmCQQaZc6L/Phone-catalog--V2--Original?node-id=15888-10208&t=eHlsynLfYMxaHFJi-0)

## Features

- Product Catalog with 3 categories: Phones, Tablets, Accessories
- Search with URL query synchronization and debounce
- Sorting options (Newest, Alphabetically, Cheapest)
- Pagination with configurable items per page
- Detailed Product Page with selectable characteristics (color, capacity)
- Favorites management (add/remove, saved in LocalStorage)
- Shopping Cart with quantity control and total calculation
- State management using React Context
- Breadcrumbs navigation
- Loading states and error handling
- Home page sliders (Hot prices & Brand new)
- Fully responsive layout for mobile(320), tablet(640), desktop(1200) and more

### Technologies Used
- HTML5
- SCSS Modules (Sass) + BEM methodology
- TypeScript
- Git
- LocalStorage
- React
- React Context
- React Router

## Description

The project follows a modular architecture with separation by pages and shared components.

- **Modules:** – contains page-based modules such as AccessoriesPage, PhonesPage, TabletsPage, CartPage, FavoritesPage, HomePage, NotFoundPage and ProductDetailsPage.
- **Components:** - reusable UI components such as BackButton, BurgerMenu, CartItem, CartSummary, Footer, Header, Loader, ProductCard, ProductsList, ProductsSlider and ShopByCategory.
- **Shared:** - constants, FetchFunction, NormalizeColorFunction, Types.

**Each component is organized as a separate folder including:**

- index.ts
- ComponentName.tsx
- ComponentName.module.scss

## ⚙️ Getting Started

#### 1.Clone the repository:

```
git clone https://github.com/DimaDamage91/Phone-Catalog-Portfolio
```

#### 2.Navigate to the project directory:

```
cd Phone-Catalog-Portfolio
```

#### 3.Install dependencies:

```
npm install
```

#### 4.Run the project locally:

```
npm start
```

#### 5.Open your browser and visit `http://localhost:3000` to view the application.

