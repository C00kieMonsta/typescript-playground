# TypeScript Playground Setup

This guide will help you set up a simple TypeScript playground locally, allowing you to quickly write and test TypeScript code.

## Prerequisites

- **Node.js**: Download and install [Node.js](https://nodejs.org/), which includes `npm`.
- **Editor**: For the best experience, use [Visual Studio Code](https://code.visualstudio.com/).

---

## Steps to Set Up the Playground

### 1. Set Up the Project

1. **Create a directory and navigate into it:**

   ```bash
   mkdir typescript-playground
   cd typescript-playground
   ```

2. **Initialize the project:**

   ```bash
   npm init -y
   ```

3. **Install TypeScript:**

   ```bash
   npm install typescript --save-dev
   ```

4. **Create a TypeScript configuration file:**
   ```bash
   npx tsc --init
   ```
   Optionally, enable `strict` mode in `tsconfig.json`:
   ```json
   {
     "compilerOptions": {
       "strict": true
     }
   }
   ```

---

### 2. Write TypeScript Code

1. **Create a `src` directory:**

   ```bash
   mkdir src
   ```

2. **Add a `playground.ts` file with the following content:**
   ```typescript
   // src/playground.ts
   const greet = (name: string): string => `Hello, ${name}!`;
   console.log(greet("TypeScript"));
   ```

---

### 3. Compile and Run the Code

1. **Compile the TypeScript file:**

   ```bash
   npx tsc src/playground.ts
   ```

2. **Run the generated JavaScript file:**
   ```bash
   node src/playground.js
   ```

---

### 4. Run Code Without Compilation (Optional)

1. **Install `ts-node`:**

   ```bash
   npm install ts-node --save-dev
   ```

2. **Run your TypeScript file directly:**
   ```bash
   npx ts-node src/playground.ts
   ```

---

### 5. Enable Auto-Reload for Changes (Optional)

1. **Install `nodemon`:**

   ```bash
   npm install nodemon --save-dev
   ```

2. **Add a script in `package.json`:**

   ```json
   "scripts": {
     "start": "nodemon --exec ts-node src/playground.ts"
   }
   ```

3. **Start the auto-reload server:**
   ```bash
   npm start
   ```

---

### Quick Reference Commands

- **Initialize Project**: `npm init -y`
- **Install TypeScript**: `npm install typescript --save-dev`
- **Create Config**: `npx tsc --init`
- **Compile Code**: `npx tsc src/playground.ts`
- **Run JS File**: `node src/playground.js`
- **Run TS File Directly**: `npx ts-node src/playground.ts`
- **Auto-Reload**: `npm start`

---
