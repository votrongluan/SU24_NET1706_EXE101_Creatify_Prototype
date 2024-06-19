# 3D Creatify Prototype

Welcome to the 3D Creatify Prototype repository! This project is a static website built using Bootstrap for prototyping a 3D-related service or product website.

## Getting Started

To get started with this project, follow these steps:

### Prerequisites

- [Git](https://git-scm.com/)
- A web browser (e.g., Chrome, Firefox, Edge)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/votrongluan/3d-creatify-prototype
   cd 3d-creatify-prototype
   ```

2. Open the `index.html` file in your web browser to view the website.

## Usage

This project is a static prototype website. You can explore the various sections and features implemented using Bootstrap.

### Examples

Here are some example sections of the website:

- Homepage with a hero section
- About Us section
- Services offered
- Portfolio of 3D projects
- Contact form

## Collaborate with Your Team

To collaborate within the team without forking, follow these steps:

### Branching Strategy

We use a Git branching strategy with three main branches:

- `main`: Contains the stable version of the code. Direct commits to this branch are restricted.
- `dev`: Contains the latest development changes. This is the main branch for ongoing development.
- `test`: Contains code that is under testing before being merged into `dev`.

### Working on a Feature

1. Create a new branch from `dev` for your feature:

   ```bash
   git checkout dev
   git pull origin dev
   git checkout -b feature/your-feature-name
   ```

2. Make your changes and commit them:

   ```bash
   git add .
   git commit -m 'Add some feature'
   ```

3. Push your branch to the repository:

   ```bash
   git push origin feature/your-feature-name
   ```

4. Create a pull request (PR) from your feature branch to `test` for testing:

   - Ensure all tests pass before requesting a merge.
   - Team members review and approve the PR.
   - Once approved, the PR is merged into `test`.

5. After thorough testing, create a pull request from `test` to `dev`.

6. For releases, create a pull request from `dev` to `main`.

### Inviting Collaborators

- Go to your repository on GitHub.
- Click on `Settings`.
- Select `Manage Access`.
- Click `Invite a collaborator` and add the GitHub usernames of your team members.

## Support

If you need help, you can reach out via:

- [Issue Tracker](https://github.com/votrongluan/3d-creatify-prototype/issues)
- [Email](mailto:support@creatify.com)

## Screenshots


## Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a pull request.

## Authors and Acknowledgment

Thanks to all the contributors who have helped develop this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Project Status

This project is actively maintained. If you would like to contribute, please feel free to fork the repository and submit a pull request.
