# **Profolio**

A privacy-focused, local-first desktop application for tailoring resumes and tracking job applications.

## **Overview**

Profolio is a desktop productivity tool designed to streamline the modern job hunt. Instead of managing spreadsheets and disparate Word documents, Profolio consolidates your interview timeline, application status, and resume tailoring into one secure, offline environment.

This repository serves as the home for all public releases of Profolio. The source code is not yet public.

## **Key Features**

- **Job Application Pipeline:** A centralized dashboard to track jobs from "Saved" to "Offer." Filter by status, date, or priority.
- **Resume Tailoring Engine:** Create a master profile of your skills and experience, then generate custom PDF resumes for specific job applications using integrated LaTeX templates.
- **Local-First Database:** All data is stored locally on your machine using SQLite. Your personal data never leaves your device.
- **Smart Resume Linking:** Upload existing PDFs or generate new ones; Profolio links them directly to the specific job application for easy retrieval during interviews.
- **Automatic Updates:** Seamless background updates via GitHub Releases.

## Tech Stack

Although the source code for this project is currently private, the application is built using the following modern stack:

- **Core:** Electron, TypeScript, Node.js
- **Frontend:** React, Vite, Tailwind CSS
- **Data:** SQLite (via better-sqlite3), IPC Bridge (Context Isolation)
- **Testing:** Jest (Unit Testing)
- **Build/CI:** Electron Builder, GitHub Actions

## Installation

#### Windows:

Go to the [releases page](https://github.com/17bryen/profolio-releases/releases) and find the latest stable release.

Download the latest Profolio-Setup-x.x.x.exe.

Run the installer.
- *Note: As this is an alpha release from an individual developer, Windows SmartScreen may warn you about an unrecognized app. You can safely click "More Info" > "Run Anyway".*

#### Linux:

Go to the [releases page](https://github.com/17bryen/profolio-releases/releases) and find the latest stable release.

Download the latest Profolio-Linux-x.x.x.AppImage.

Once downloaded, open terminal and run the following command to set the file as executable:

``` chmod +x Profolio-Linux-x.x.x.AppImage ```

Double-click the file to run the AppImage.

## Feedback & Issues

This application is currently in early development. You almost certainly will encounter bugs or incomplete features.
There is currently no standard feedback template or pipeline, but if you find an issue in one of the builds, please [open an issue](https://github.com/17bryen/profolio-releases/issues) in this repository.
