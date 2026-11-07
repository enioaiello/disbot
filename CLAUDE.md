# Claude instruction file

This file help Claude to understand the project.

## Introduction

You work on a moderation/security Discord bot. The bot you work on is pretty basic, but follow a few rules.

## Rules

1. Made the task and operation simple: use basic Discord settings, don't made the usage of the bot complicated.
2. Use Discord functions and APIs: use slash commands, embed…
3. The bot needs to be efficiant, not pretty: only tell the informations needed (/ban indicate, for example, only who has been banned and the reason). The embed only needs a title and a content (exception can be made).

## Modules

### Moderation

The user (with the appropriated rights) can use these commands:
- Warn: warn an user, always with a reason
- Kick: expulse an user, can provide a reason
- Tempban: ban an user for a fixed amount of time, always with a reason
- Ban: ban an user definitively, always with a reason
- Mute: mute an user definitively, always with a reason
- Tempmute: mute an user for a fixed amount of time, always with a reason
- Auto-moderator: block ads, block staff ping

### Security

The user with an administrator permission can use these commands:
- Lock a channel: the user can lock a specific channel
- Lock all channels: the user can lock all channels (make sure to note which channels was already lock)
- Templock a channel: the user can lock a specific channel for a certain amount of time
- Templock all channels: the user can lock all channels for a certain amount of time
- Captcha: the user can setup a captcha system which allows the new members to enter something to access the server
- Anti-hacked account: the user can setup an anti-hacked account which need to setup a channel where users don't write unless they want to be kicked
- Anti-multiple account: provide a function that can detect and block alt account
- Fast spam message: detect and block fast spam message

## Experience

- Users can set up which function is in use and specific settings for functions entirely in Discord

## Commands

### Specific

- help: display the help menu
- ping: check the ping of the bot
- setup: setup the bot (same command for config)

### Others commands

Use the [modules section](#) to see which commands needs to be implemented.

## Developement

When working:
1. Check for existing code
2. Respect the work method
3. Verify if the writted code is well integrated with the rest of project
4. Check for accessibility, security and performance issues. If present, fix them
