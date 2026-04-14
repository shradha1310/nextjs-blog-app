# 🚀 Next.js Blog App (App Router + Server Components)

This project is a modern blog listing application built using **Next.js (App Router)**. It demonstrates how to use **Server Components**, **SSR data fetching**, and **hybrid architecture (Server + Client components)** for optimal performance and scalability.

---

## 📌 Features

* ⚡ Built with Next.js App Router
* 🧠 Server Components (default rendering)
* 🌐 Server-side data fetching (SSR)
* 🎯 Clean and scalable folder structure
* 🎨 Styled using Tailwind CSS

---

## 📡 API Used

```
https://api.vercel.app/blog
```

---

## 🏗️ Project Structure

```
app/
  ├── layout.tsx        # Root layout
  ├── page.tsx          # Blog listing page (Server Component)
```

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/nextjs-blog-app.git
cd nextjs-blog-app
```

---

### 2. Install dependencies

```bash
npm install
```

---

### 3. Run the development server

```bash
npm run dev
```

---

### 4. Open in browser

```
http://localhost:3000
```

---

## 🧠 Key Concepts Demonstrated

### ✅ Server Components

* Default in Next.js App Router
* Run on server
* No client-side JavaScript
* Better performance and SEO

---

### ✅ Data Fetching (SSR)

```ts
fetch(url, { cache: 'no-store' })
```

* Always fetch fresh data
* Runs on server

---

## 🚀 Future Improvements

* 🔗 Dynamic routing (`/blog/[id]`)
* 📄 Blog detail page
* 🔍 Search and filtering
* 📦 API abstraction layer (`utils`)
* 🧪 Unit testing
* 🌍 Deployment on Vercel

---

---

## 🧑‍💻 Author

* Shradha

---

## 📄 License

This project is open-source and available under the MIT License.

---

## ⭐ Acknowledgements

* Next.js Documentation
* Vercel API
