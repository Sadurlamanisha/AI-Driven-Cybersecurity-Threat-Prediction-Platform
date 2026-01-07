Threat Predict
Threat Predict is a comprehensive security monitoring and scanning platform built with modern web technologies. It provides real-time threat detection, AI-powered predictions, and various security scanning tools to ensure the integrity and safety of your digital assets.

🚀 Key Features
🛡️ Real-time Monitoring
Live Threat Map: Interactive visualization of global security threats using Three.js.
Analytics Dashboard: Comprehensive view of security metrics and attack patterns.
Threat Feed: Real-time stream of security incidents and blocked attacks.
Globe View: 3D globe visualization for geographic threat analysis.
🔍 Advanced Scanners
Website Scanner: Comprehensive vulnerability assessment for web applications.
API Scanner: Security auditing for RESTful endpoints.
QR Scanner: Secure QR code analysis and verification.
Static Scanner: File-based security analysis.
🤖 AI-Powered Insights
Threat Predictions: Machine learning-driven analysis to anticipate potential security breaches.
Incident Management: Automated tracking and resolution workflow for security alerts.
👥 Management & Security
User Management: Role-based access control and user activity tracking.
Secure Authentication: Robust auth system powered by Supabase.
Customizable Settings: Fine-tune scanning parameters and monitoring preferences.
🛠️ Tech Stack
Frontend: React + TypeScript + Vite
Styling: Tailwind CSS + shadcn/ui
Visualization: Three.js (@react-three/fiber) + Recharts
Backend/Database: Supabase
State Management: TanStack Query
Forms & Validation: React Hook Form + Zod
🏁 Getting Started
Prerequisites
Node.js (v18 or higher)
npm or bun
Installation
Clone the repository

git clone <repository-url>
cd threat-predict
Install dependencies

npm install
# or
bun install
Environment Setup Create a .env file in the root directory and add your Supabase credentials:

VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
Run Development Server

npm run dev
The application will be available at http://localhost:8080.

🏗️ Project Structure
src/pages: Main application views (Dashboard, Scanners, Monitors, etc.)
src/components: Reusable UI components built with shadcn/ui.
src/hooks: Custom React hooks for logic reuse.
src/integrations: Supabase and other third-party integrations.
supabase/: Database migrations and edge functions.
📄 License
This project is licensed under the MIT License.





Footer navigation
Terms
Pri
