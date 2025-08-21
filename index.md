# Stop there

![Image of Yaktocat](https://thumbs.dreamstime.com/b/devil-face-sri-lankan-yaka-mask-ves-muna-yak-muna-sri-lankan-traditional-face-vector-mask-devil-face-sri-lankan-yaka-mask-ves-muna-315977495.jpg)

```
// Import Express
const express = require('express');

// Create an Express app
const app = express();

// Middleware to parse JSON bodies
app.use(express.json());

// Define a simple route
app.get('/', (req, res) => {
  res.send('Hello World! This is your Express server running on port 5000.');
});

// Example API route
app.get('/api/users', (req, res) => {
  const users = [
    { id: 1, name: 'Thushitha' },
    { id: 2, name: 'Thakshila' },
  ];
  res.json(users);
});

// Start the server on port 5000
const PORT = 5000;
app.listen(PORT, () => {
  console.log(`Server is running on http://localhost:${PORT}`);
});

```


# My To-Do List

- [ ] Learn Markdown basics
- [ ] Create a README for my project
- [x] Set up local Node.js server
- [ ] Build Express API routes




