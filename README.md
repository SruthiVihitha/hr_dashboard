# HR Performance Dashboard - README

![Dashboard Screenshot](./public/screenshot.png)

## 📝 Overview

A modern HR dashboard built with Next.js that allows HR managers to track employee performance, manage bookmarks, and view detailed analytics. The application features responsive design, dark/light mode, and interactive data visualization.

## ✨ Features

### Core Features
- **Employee Dashboard**: View and manage employee profiles
- **Search & Filter**: Find employees by name, department, or rating
- **Employee Details**: Detailed profiles with performance history
- **Bookmark Manager**: Save and organize important profiles
- **Analytics**: Visualize department performance and trends

### Advanced Features
- **Dark/Light Mode**: Toggle between color schemes
- **State Management**: Zustand for global state
- **Responsive Design**: Works on all device sizes
- **Dynamic Routing**: Employee detail pages
- **Chart Visualizations**: Performance analytics

### Bonus Features
- **Authentication**: Protected routes with NextAuth
- **Form Validation**: Add new employees
- **Animations**: Smooth UI transitions

## 🛠️ Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **Charts**: Chart.js
- **Authentication**: NextAuth.js
- **Icons**: Heroicons
- **Animation**: Framer Motion

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hr-dashboard.git
   cd hr-dashboard
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Create a `.env.local` file:
   ```env
   NEXTAUTH_SECRET=your-secret-key
   NEXTAUTH_URL=http://localhost:3000
   ```

4. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📂 Project Structure

```
src/
├── app/
│   ├── (auth)/                   # Authentication routes
│   ├── (dashboard)/              # Protected dashboard routes
│   │   ├── analytics/            # Analytics page
│   │   ├── bookmarks/            # Bookmarks manager
│   │   ├── employee/             # Employee details
│   │   └── page.tsx              # Dashboard home
│   ├── api/                      # API routes
│   └── layout.tsx                # Root layout
├── components/                   # Reusable components
├── context/                      # Context providers
├── hooks/                        # Custom hooks
├── lib/                          # Utilities and config
├── styles/                       # Global styles
└── providers.tsx                 # App providers
```

## 🔧 Customization

### Environment Variables
- `NEXTAUTH_SECRET`: Secret key for authentication
- `NEXTAUTH_URL`: Base URL for authentication callbacks

### Styling
Edit the Tailwind config in `tailwind.config.ts` to customize:
- Color scheme
- Font family
- Breakpoints

## 📸 Screenshots

| Light Mode | Dark Mode |
|------------|-----------|
| ![image](https://github.com/user-attachments/assets/07031341-7807-4aea-ac24-53879a8c3c2f)
| ![image](https://github.com/user-attachments/assets/d95bddae-ddf4-448d-b104-75a89a9f1846)
![image](https://github.com/user-attachments/assets/0329bc56-620d-46c7-a388-71290a6c4dc7)
![image](https://github.com/user-attachments/assets/2f7effc6-7493-4052-855f-e597c121b051)

|

| Dashboard | Analytics |
|-----------|-----------|
| ![image](https://github.com/user-attachments/assets/5fb32a63-41f6-4ab6-8844-41319719726e)

 |![image](https://github.com/user-attachments/assets/c490499d-d4bc-4a47-a1b7-9ad6790ed394)
 |

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📧 Contact

mail to: sruthivihitha_potluri@srmap.edu.in

Project Link: 

