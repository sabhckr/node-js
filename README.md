# ostad-module-3-ci-cd

## Prerequisites

- Node Version 22

### 1. For Run This Application
npm install  
npm run check  
npm start

### Deployment Process
pm2 delete node-app || true  
pm2 start "./src/server.js" --name node-app  
pm2 save

### About The Application
- `/`       # shows a hello world page  
- `/api`    # responds with JSON  

# Default port is 3000
