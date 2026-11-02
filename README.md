# Device Store | LAmAY

A responsive online store for browsing and purchasing gadgets. Explore smartphones, tablets, and accessories, view detailed product information, choose product variants, and manage your shopping cart and favourites.

Live Preview

[Visit Device Store](https://olenabokhan1121.github.io/-device-store-lamay/)

Technologies Used

- React — building the user interface
- TypeScript — static typing
- Vite — development environment and build tool
- Tailwind CSS — styling and responsive layouts
- Zustand — state management
- React Router — client-side routing
- Base UI / shadcn — UI components
- EmailJS — email functionality

Getting Started

Follow these steps to run the project locally.

1.  Clone the repository

bash
git clone https://github.com/olenabokhan1121/-device-store-lamay.git
cd ./-device-store-lamay

2. Install dependencies

```bash
npm install
```

3. Configure environment variables

Create a `.env` file in the root directory of the project using `.env.example` as a template.

Add the required environment variables:

```env
VITE_GADGETS_URL=your_gadgets_api_url
VITE_EMAILJS_SERVICE_ID=your_emailjs_service_id
VITE_EMAILJS_TEMPLATE_ID=your_emailjs_template_id
VITE_EMAILJS_PUBLIC_KEY=your_emailjs_public_key
```

Replace the placeholder values with your actual configuration.

4. Run the project locally

bash
npm run dev

Open the local URL provided by Vite in your terminal.

Features

- Browse products by category.
- View detailed product information.
- Explore product image galleries.
- Select available product colors and storage capacities.
- Add products to the shopping cart.
- Add and remove products from favourites.
- View recommended and similar products.
- Navigate between product variants without reloading the page.
- Responsive layout for different screen sizes.
- Contact page with team information and GitHub profiles.
