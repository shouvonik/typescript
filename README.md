# typescript
# Project Setup Instructions

## Prerequisites
Ensure you have the following tools installed before proceeding:
- **nvm (Node Version Manager)**
- **Node.js** (LTS version)
- **npm**
- **TypeScript**

---

## Installation Steps

### 1. Install Node.js (LTS Version) Using nvm
Use the following commands to install the LTS version of Node.js via nvm:

```bash
nvm install --lts
```

Verify the installed versions:

```bash
node -v      # Check Node.js version
npm -v       # Check npm version
```

Example Output:
```bash
node v22.12.0
npm v10.9.0
```

---

### 2. Install TypeScript Globally
Install the TypeScript compiler globally using npm:

```bash
npm install -g typescript
```

Verify the TypeScript version:

```bash
tsc -v
```

Example Output:
```bash
Version 5.7.2
```

---

## Summary of Commands
For quick reference, here are all the commands in one place:

```bash
nvm install --lts
node -v
npm -v
npm install -g typescript
tsc -v
```

---

## Next Steps
You are now ready to use TypeScript with Node.js. Start writing your TypeScript code and compile it using:

```bash
tsc <file-name>.ts
```

For additional configuration, consider creating a **tsconfig.json** file for your project.

---

### Need Help?
If you encounter any issues, please open an issue in this repository. Happy coding! 🚀

