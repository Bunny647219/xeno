# Shopify Data Ingestion & Insights Service
Front end site link:https://exact-poet-77042603.figma.site/

A multi-tenant Shopify analytics dashboard built with React, TypeScript, and Tailwind CSS that simulates how enterprise retailers can onboard, integrate, and analyze their customer data.

## 🚀 Features

- **Multi-tenant Architecture**: Secure data isolation for multiple Shopify stores
- **Real-time Analytics**: KPIs including total customers, orders, and revenue
- **Interactive Charts**: Orders over time and top customers by spend
- **Advanced Date Filtering**: Custom date ranges with smart validation
- **Professional UI**: Modern, minimalist design with responsive layout
- **Performance Optimized**: Lazy loading, caching, and memoization

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript + Vite
- **Styling**: Tailwind CSS v4 + shadcn/ui components
- **Charts**: Recharts for data visualization
- **Authentication**: JWT-based with secure session management
- **Icons**: Lucide React
- **Animations**: Motion (Framer Motion)

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/shopify-data-insights.git
cd shopify-data-insights
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 🎯 Usage

### Authentication
- **Demo Login**: Use any email/password combination
- **Shop Domain**: Enter any `.myshopify.com` domain for demo purposes

### Dashboard Features
- **Date Range Selection**: Choose from presets or create custom ranges
- **KPI Monitoring**: Track revenue, orders, and customer metrics
- **Data Visualization**: Interactive charts with hover details
- **Export Options**: Download reports and charts

## 🏗️ Project Structure

```
src/
├── components/           # React components
│   ├── ui/              # shadcn/ui base components
│   ├── figma/           # Figma-specific components
│   ├── Dashboard.tsx    # Main dashboard
│   ├── AuthForm.tsx     # Authentication forms
│   └── ...             # Other components
├── lib/                 # Utility functions
│   ├── auth.ts         # Authentication logic
│   ├── mockData.ts     # Demo data generation
│   └── dateUtils.ts    # Date manipulation utilities
├── types/              # TypeScript type definitions
├── styles/             # Global CSS and Tailwind config
└── App.tsx            # Root component
```

## 🔧 Development

### Building for Production
```bash
npm run build
```

### Linting
```bash
npm run lint
```

### Preview Production Build
```bash
npm run preview
```

## 🎨 Design System

The application follows a professional blue color scheme:
- **Primary**: #4A90E2 (Professional blue)
- **Accent**: #50E3C2 (Mint green)
- **Typography**: Inter/Nunito Sans fonts
- **Layout**: Responsive grid system with mobile-first approach

## 📊 Demo Data

The application includes simulated Shopify data:
- **Customers**: Realistic customer profiles with purchase history
- **Orders**: Various order states and financial statuses
- **Products**: Sample product catalog with pricing
- **Multi-tenant**: Data isolation by shop domain

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Set build command: `npm run build`
3. Set output directory: `dist`
4. Deploy automatically on git push

### Netlify
1. Connect repository to Netlify
2. Build command: `npm run build`
3. Publish directory: `dist`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit changes: `git commit -m 'Add amazing feature'`
4. Push to branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Vite](https://vitejs.dev/) and [React](https://reactjs.org/)
- UI components from [shadcn/ui](https://ui.shadcn.com/)
- Icons by [Lucide](https://lucide.dev/)
- Charts powered by [Recharts](https://recharts.org/)
