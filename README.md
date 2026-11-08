# Forge by UI8 for Claude

**A visual brain for your agents.**

Forge is a design and prototyping tool built on live, reusable UI: landing page sections, app screens, dashboards, animated heroes, shader backgrounds and video. With the Forge plugin, describe what you need, find the piece that fits, preview it live, and make it part of your work.

Explore each project's components and adjustable props, and compare directions side by side before you commit. Publish any project to its own link to share for review, gather comments and proposed edits from your team, and resolve them in one place. Organize your work into collections, with skills that capture how each piece should be used, so every agent designs and builds with the same visual language.

Forge supports designers, product managers, founders, marketers, developers and teams building a consistent design system. Keep shared UI together in team workspaces and remix collections from others. In a coding environment with file access, pull React components into your project, adapted to its code and conventions, or create and edit projects to keep refining them.

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
