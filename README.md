# Angular Microfrontend Practice
A learning project demonstrating Microfrontend architecture using Angular. This setup includes multiple Angular applications working together as independent frontends, built and deployed separately, but composed into a single UI shell.

# Purpose
This project is built to understand and practice Microfrontend concepts with Angular using tools like Module Federation, Custom Elements, or iframe-based integration.

# Features
- Multiple Angular microfrontends.
- Independent builds & deployments for each MFE.
- Integration using Webpack Module Federation (or other approach used).
- Shared dependencies optimized to reduce bundle size.
- Lazy loading of remote modules/components.


# Setup & Run
Clone Repo
- git clone https://github.com/your-username/your_repo_name.git
- cd your_folder_name
- `npm install`

# Run Microfrontends Individually
ng serve angular-mfe-example
ng serve remoteapp1
ng serve remoteapp2

# Notes
- Designed for learning purposes only.
- Assumes local development setup.
- Ensure ports don’t conflict; adjust in angular.json if needed.

---

# Contributions

This project is for educational/demo purposes. Thanks for checking it out!

