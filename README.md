# GoodBots for GitHub
Curated lists of IP addresses/whitelists of good bots and crawlers. BUT ONLY GITHUB.

All IP-Lists are in the [CIDR-Notation](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing) and can be used as whitelists in your webserver's firewall or as an exception for rate-limits.

Either use the [all.ips](all.ips) list or a specific service's list of IP-Addresses found in the [iplists/](iplists/) directory.

The lists are updated daily via a scheduled GitHub Action.

  
```
.
├── all.ips 
│   Combined List of all IP addresses found in iplists/
│
└── iplists/
    │
    ├── github-actions.ips
    │   IP-Addresses used by the GitHub Actions
    │   
    ├── github-api.ips
    │   IP-Addresses used by the GitHub API
    │   
    ├── github-codespaces.ips
    │   IP-Addresses used by the GitHub Codespaces
    │   
    ├── github-copilot.ips
    │   IP-Addresses used by the GitHub Copilot
    │   
    ├── github-dependabot.ips
    │   IP-Addresses used by the GitHub Dependabot
    │   
    ├── github-git.ips
    │   IP-Addresses used by the GitHub Git
    │   
    ├── github-enterprise_importer.ips
    │   IP-Addresses used by the GitHub Enterprise Importer
    │   
    ├── github-hooks.ips
    │   IP-Addresses used by the GitHub Hooks
    │   
    ├── github-importer.ips
    │   IP-Addresses used by the GitHub Importer
    │   
    ├── github-packages.ips
    │   IP-Addresses used by the GitHub Packages
    │   
    ├── github-pages.ips
    │   IP-Addresses used by the GitHub Pages
    │
    └── github-web.ips 
        IP-Addresses used by the GitHub Web
        
```
