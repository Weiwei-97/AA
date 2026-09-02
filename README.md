# 🌊 Alon Aninag Boutique Beach Resort
> Sipalay City, Negros Occidental, Philippines

A responsive web application for **Alon Aninag Boutique Beach Resort**, featuring online bookings, interactive resort navigation, local attractions map, live concierge chat, offline travel itinerary mode, and multi-currency pricing.

---

## ✨ Features

- 🏖️ **Villa & Room Showcase**: Complete gallery, amenities, capacity, and live rate calculation.
- 📅 **Direct Booking Engine**: Multi-step booking modal with instant confirmation codes and printable receipts.
- 🗺️ **Interactive Sipalay Map**: Explore local beaches, dive spots (Tinagong Dagat, Sugar Beach, Campomanes Bay), and resort facilities.
- 💬 **Live Concierge Chat**: Immediate simulated resort assistant for guest inquiries.
- 📱 **Offline Itinerary Mode**: Saves your reservations and offline emergency guides to local storage.
- 💱 **Multi-Currency & Multi-Language Support**: Real-time conversion across PHP, USD, EUR, JPY, AUD, GBP and multilingual translations.
- 🛡️ **Admin Portal**: Reservation tracking and check-in status manager.

---

## 🚀 How to Deploy on GitHub Pages

The repository includes a ready-to-use GitHub Actions workflow (`.github/workflows/static.yml`).

### Step-by-Step GitHub Pages Setup:

1. **Push your code** to your GitHub repository on the `main` branch.
2. In your GitHub repository, navigate to **Settings** > **Pages** (under the "Code and automation" section).
3. Under **Build and deployment**:
   - **Source**: Select **GitHub Actions**.
4. GitHub Actions will automatically trigger the build (`npm run build`) and deploy the compiled `dist/` directory to your GitHub Pages URL (e.g., `https://<username>.github.io/<repository-name>/`).
5. Open your deployed link and enjoy the live resort website!

---

## 💻 Local Development

### Prerequisites
- Node.js 18+ or 20+
- npm or yarn

### Installation
```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

# Install dependencies
npm install

# Start local development server
npm run dev
```
Visit `http://localhost:3000` to view the app in your browser.

### Building for Production
```bash
npm run build
```
This produces optimized static assets in the `dist/` directory.

---

## 🛠️ Tech Stack
- **Framework**: React 19 + TypeScript
- **Build Tool**: Vite 6 (configured with `/AA/` base path for GitHub Pages)
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Animations**: Motion (Framer Motion)
