This is my personal website built with [Hugo](https://mkcyberlabs.in/).  
The site is generated from this repository and deployed on [GitHub Pages / Netlify / Vercel].

## 🚀 Installation & Setup

### 1. Prerequisites
- [Git](https://git-scm.com/)
- [Hugo Extended](https://gohugo.io/getting-started/installing/)
- [Node.js](https://nodejs.org/) (LTS recommended, for frontend assets like Tailwind/PostCSS)
- Optional: [Go](https://go.dev/) (if you plan to build custom Hugo modules)

---

### 2. Clone the repository
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

3. Install Node dependencies

If your theme uses Node (e.g., TailwindCSS, PostCSS, etc.):

npm install

4. Run locally

Start a local development server with drafts enabled:

hugo server -D


If your project has extra frontend tooling:

npm run dev


Then open 👉 http://localhost:1313

5. Build the site Generate the static files:

hugo

6. If Node build is required (e.g., TailwindCSS):

npm run build
