# Overview
This guide provides the cut-and-dry steps that we will walk through during the GitHub Advanced Security Certification Workshop.

# Module 1
1. Sign in to github.com
2. Click on your avatar in the top right corner
3. Click on `Your organizations`
4. Look for an organization that follows the format `ghas-bootcamp-DATE-HADNLE` where `DATE` is today's date and `HANDLE` is your handle
5. Ensure the organization has `5` repositories
6. In the `ghas-bootcamp-webgoat` repository, go to **Settings** -> **Code security and analysis** and then click **Enable** for _Dependency graph_, _Dependabot alerts_, _Dependabot security updates_, and **GitHub Advanced Security**
7. Navigate back to the organization and create a new repository named `public-repo` with the visibility option set to `public` and the `Add a README file` box **checked**
8. Navigate to the repository's settings tab and view the Code security & analysis page
9. Notice that **Dependency Graph is always on by default**, **there is no Advanced Security button**, (it's not needed to enable secret scanning & code scanning for public repos), **Secret scanning sends alerts to partners by default**
10. Navigate back to the organization and then Settings -> Code Security and Analysis and click Enable all for _Dependency graph_, _Dependablot alerts_, _Dependabot security updates_, and _GitHub Advanced Security_.
