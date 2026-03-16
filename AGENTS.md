# AGENTS.md

## Project Workflow

- Use the GitHub MCP as the primary way to manage repository changes for this project.
- The GitHub repository for this project is `Llindley/FXServices`.
- Prefer updating files in the GitHub repo directly when making user-requested project changes.
- After making changes, push them to the GitHub project unless the user explicitly asks not to.

## Deployment Workflow

- Use the Cloudflare MCP to manage deployment-side work for this project.
- The Cloudflare Pages project name is `fxservices`.
- The production branch is `main`.
- The production site is available at `https://fxservices.org`.
- The Pages subdomain is `https://fxservices.pages.dev`.

## Notes

- Local workspace files may be used for inspection, drafting, or validation, but GitHub and Cloudflare are the operational source of truth for this project.
- When verifying deployment, confirm that the latest Cloudflare Pages production deployment matches the latest pushed GitHub commit when possible.
