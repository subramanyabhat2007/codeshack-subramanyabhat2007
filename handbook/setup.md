# Git Installation and Configuration
## 1. Installing Git

I started by downloading Git for Windows from the official Git website. After downloading the installer, I ran it and followed the installation wizard. I kept the recommended default settings throughout the installation process and completed the setup.

Once Git was installed, I opened Git Bash, which provides a command-line interface for executing Git commands. To verify that the installation was successful, I executed the following command:

```bash
git --version
```

This command displayed the installed version of Git, confirming that it was installed correctly and ready to use.

## 2. Configuring Git Username and Email

After installing Git, I configured my username and email address. These details help Git identify the author of each commit I make. Whenever I save changes to a repository using `git commit`, Git records this information in the commit history.

I used the following commands to configure my identity:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

I replaced `Your Name` with my preferred name and `your-email@example.com` with my email address.

The `--global` option applies these settings to all Git repositories for my Windows user account, unless a repository has its own local configuration.

## 3. Verifying the Configuration

After setting my username and email, I verified that Git had saved the details correctly by running:

```bash
git config --global user.name
git config --global user.email
```

Git displayed the configured username and email address as output.

I also learned that these settings identify the author of my commits but do not, by themselves, authenticate me to GitHub. GitHub authentication is configured separately when pushing changes to a remote repository.

## Conclusion

Through this process, I learned how to install Git, verify the installation, and configure my identity using the command line. This setup is an important first step in using Git for version control, tracking changes, maintaining commit history, and collaborating with others on GitHub.
