# Welcome to the Bigstone Community Web

## Local Setup

### 1. Initialize Local Database *(one-time)*

```bash
wrangler d1 execute community-web --local --file=sql/local.sql
```

### 2. Start Local Development Server

```bash
wrangler pages dev public
```

---

## Development

### 🧩 Franken UI Import

Add this script to your HTML to use the Franken UI:

```html
<script src="/public/javascript/ui/franken.js" type="module"></script>
```


---

## 📂 Project Functions

- [ ] **Main Page**
  - [ ] Login button  
  - [ ] Links to Bigstone development projects

- **App Page**
  - Application UI and logic
