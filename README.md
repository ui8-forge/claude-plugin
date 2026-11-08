# Forge by UI8 for Claude

**A visual brain for your agents.**

Forge is an AI design and prototyping tool for creating interactive websites, app interfaces, dashboards and animated UI. With the Forge plugin, describe what you want to make and turn your ideas, references or existing UI into live, editable work you can explore and refine.

Create a landing page, prototype an app screen, or build an animated hero or shader background with working interactions. Compare design directions side by side, tune them with adjustable controls, and save reusable skills and brand files for a consistent look. Publish any project to its own link for review, gather comments and proposed edits from your team, and resolve them in one place.

Forge supports designers, product managers, founders, marketers, developers and teams building a consistent design system. Keep related work together in collections and team workspaces, and remix collections others share. In a coding environment with file access, bring Forge projects into your app as React components adapted to its code, or create and edit projects to keep refining them.

This plugin brings Forge into Claude and Claude Code. It connects to the Forge server at `https://forge.ui8.ai/mcp` and adds a skill that teaches Claude how to use your projects well.

## What you can do

In the Claude apps:

- Describe what you're picturing and find the projects that match, across all your workspaces.
- Share a project on its own ui8.dev page, locked to the people you choose if you like, and take it down whenever you want.
- Read the comments and suggested changes people leave, reply to them, and mark them done.
- Keep your library organized: start collections, then move, rename, tag and archive projects (you can always bring archived ones back), or remix a shared collection into your own workspace.

In Claude Code:

- Reuse what you've already made. Before building something new, Claude checks your Forge projects and follows their guidelines, then adds the right one to your codebase so it fits, with a link back to the original.
- Create new projects or refine existing ones, then open the live workbench to see the result.
- Write guidelines for how your projects should be used, so every agent works in the same style.

## Install

**Claude Code**

```
/plugin marketplace add ui8-forge/claude-plugin
/plugin install forge-ui8@ui8-forge
```

**Claude apps:** Customize › Plugins › Add › Add marketplace, then enter `ui8-forge/claude-plugin` and add Forge by UI8.

The first time Claude uses Forge, it asks you to sign in. You sign in once with your Forge email, and the plugin can only see the workspaces you belong to.

## Requirements

A Forge account. [Get Forge](https://ui8.ai/forge/).

## Links

- Documentation: https://ui8.ai/forge/docs
- Support: support@ui8.ai · https://forge.ui8.ai/support
- Privacy policy: https://forge.ui8.ai/privacy
- Terms of service: https://forge.ui8.ai/terms
