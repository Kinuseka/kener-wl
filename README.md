# BitStatus

This project is a fork of [Kener](https://github.com/rajnandan1/kener), an open-source status page system built with Svelte and TailwindCSS, licensed under the MIT License.

---


## About

This fork is modified to suit our specific needs.

## Quick StartUp

### Requirements

- Node.js (version 20 or higher recommended)
- Git
- sqlite3 (or another supported database)

### 1. Clone the repository

```bash
git clone <your-fork-url>
cd <your-project-directory>
```

### 2. Install dependencies

```bash
npm install
```

### 3. Set up environment variables

Create a `.env` file in the root directory. At minimum, set these required variables:

```
KENER_SECRET_KEY=your-strong-secret-key
ORIGIN=http://localhost:3000
```

You can add more variables as needed. See `docs/environment-vars.md` for all options.

### 4. Start the development server

```bash
npm run dev
```

The app will be running at [http://localhost:3000](http://localhost:3000)

- Status page: [http://localhost:3000](http://localhost:3000)
- Manage portal: [http://localhost:3000/manage/app/site](http://localhost:3000/manage/app/site)

### 5. First-time setup

On first launch, you'll be redirected to the setup page. Create your admin user by filling in the form (name, email, password). Passwords must be at least 8 characters, with uppercase, lowercase, and numbers.

After setup, log in at [http://localhost:3000/manage/signin](http://localhost:3000/manage/signin)

---

## License

Original MIT License applies. See LICENSE file.