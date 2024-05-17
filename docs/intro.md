---
sidebar_position: 1
---

# Introduction

⚡️ **CashierApp** will help you manage complex sales in an easier way.

💸 Based on **Java Swing**, **Postgresql**. with strong community support of this technology makes this application **robust and reliable**.

💅 Using **[Flatlaf](https://www.formdev.com/flatlaf/)** library to make the ui very modern and interactive.

## Getting Started

Start with the installation of some necessary applications.

**Why do I have to install another application first?** for now **CashierApp** needs some additional applications to run smoothly.

### What you'll need

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.
- [JDK](https://www.oracle.com/id/java/technologies/downloads/) version 20.0 or above:
- [Postgresql](https://www.postgresql.org/) version 14.0 or above:
- [Git](https://git-scm.com/downloads) version 2.45.0 or above:

## Installation

Clone source code to your local computer using **git** :

```bash
git clone https://github.com/manikandareas/swing-pos.git
```

You can type this command into Command Prompt, Powershell, Terminal, or any other integrated terminal of your code editor.

The command will be clone entire source code to your computer.

Run migration with **drizzle-kit** :

```bash
cd swing-pos\server
npm install
npx drizzle-kit push:pg
```

## Start your app

Run **CashierApp** :

```bash
java -jar swing-pos.jar
```

The `cd` command changes the directory you're working with. In order to work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm install` command to install entire dependencies needed.

The `npx drizzle-kit push:pg` command to run migration database.

The `java -jar` command to execute and running application jar.
