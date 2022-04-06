# HMR issue

The HMR doesn't update the data on page.

Steps to reproduce:

1. Install dependencies and run project

```bash
npm install
npm run dev
```

Open app on `http://localhost:3000`

2. Open `app.vue` and try changing `counter` value inside script tag and save.

Result: The counter value is not updated on page. Try refreshing - new value appears.

3. Change anything in template and save.

Result: The page is updated automatically without needing refresh.
