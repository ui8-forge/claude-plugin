# Forge by UI8 for Claude

**A visual brain for your agents.**

[Forge](https://ui8.ai/forge/) Fragments are small, live pieces of interface: a shader you can play with, a motion study, a music player, a tiny game, an onboarding flow. Each one lives at its own link, comes with variations to flip between and settings to tweak, and sits in a collection with guidelines for how it's meant to be used and the files that go with it.

This plugin brings Forge into Claude and Claude Code. It connects to the Forge server at `https://forge.ui8.ai/mcp` and adds a skill that teaches Claude how to use your fragments well.

## What you can do

In the Claude apps:

- Describe what you're picturing and find the fragments that match, across all your workspaces.
- Share a fragment on its own ui8.dev page, locked to the people you choose if you like, and take it down whenever you want.
- Read the comments and suggested changes people leave, reply to them, and mark them done.
- Keep your library organized: start collections, then move, rename, tag and archive fragments (you can always bring archived ones back), or remix a shared collection into your own workspace.

In Claude Code:

- Reuse what you've already made. Before building something new, Claude checks your fragments and follows their guidelines, then adds the right fragment to your project so it fits, with a link back to the original.
- Create new fragments or refine existing ones, then open the live workbench to see the result.
- Write guidelines for how your fragments should be used, so every agent works in the same style.

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
