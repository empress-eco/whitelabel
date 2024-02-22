<p align="center">
<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo">
</p>

<h1 align="center">
Empress Whitelabel: The Ultimate Customization Power For Your Workspace
</h1>

<p align="center">
A dynamic tool for personalizing your Empress workspace to enhance brand identity and user experience.
<br />
<a href="https://grow.empress.eco/">Explore the Docs</a>
·
<a href="https://github.com/empress-eco/whitelabel/issues">Report a Bug</a>
·
<a href="https://github.com/empress-eco/whitelabel/issues">Request a Feature</a>
</p>

## About The Project

Empress Whitelabel is a powerful tool developed for businesses that utilize Empress and wish to customize their workspace to mirror their branding and user preferences. This tool not only enhances your brand identity but also provides a unique experience for your users. 

### Key Features

- Customize App Logo, Favicon, and Splash Image
- Manage Navigation Bar's Background Color and Title
- Update Onboard Steps (Version 13)
- Hide Help Menu and "Powered by" Text
- Customize Login Page Title
- Disable New Updates Popup

## Technical Stack and Setup Instructions

Empress Whitelabel is built on the robust and reliable Empress framework.

**Prerequisites:** You need to have Empress installed on your server.

**Installation:**

```sh
# Clone the repository
bench get-app https://github.com/empress-eco/whitelabel.git

# Install the app for a specific site
bench --site your_site_name install-app whitelabel

# Migrate the database
bench --site your_site_name migrate

# Restart the bench
bench restart

# Clear the cache
bench clear-cache
```

## Usage

After installation, navigate to the Whitelabel settings page to start customizing your workspace. You can adjust the App logo size, manage the Navigation Bar, update the welcome blog post, and more.

## Contribution Guidelines

We welcome your contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgments

This project is under the MIT License. Your contributions are also licensed under the same.

A special thanks to the Empress Community, the original architects behind the foundational tools that power this project. Their innovation and dedication have been instrumental to our work and we are profoundly grateful for their pioneering efforts and ongoing support.