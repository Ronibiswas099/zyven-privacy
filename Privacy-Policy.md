# Zyven Privacy Policy

**Effective date: November 16, 2026**

Zyven is a multipurpose Discord bot developed by Zyven Development. This policy explains the information the bot processes, how it is used, where it may be stored or shared, and how to request access or deletion.

## Information processed

Depending on the bot features enabled in a server, Zyven may process:

- **Discord account and server data:** Discord user, server, channel, role, and message IDs; usernames and display names; avatars; member roles and join times; and server configuration.
- **Presence and member data:** Member join, leave, role, and moderation events; member and server counts; and, when the server configures vanity roles or status features, a member's custom status or presence information needed to apply or remove a role or show a requested status summary. Zyven does not need presence data for every feature.
- **Message content:** Message text is read to detect prefix commands and operate features such as moderation, AutoMod, anti-spam, autoresponders, autoreactions, leveling, and configured AI chat. If a server enables message event logging, edited or deleted message text and available attachment links may be posted to that server's configured log channel. Server administrators control those channels and their access.
- **Moderation and security records:** Warnings and other moderation actions, audit-related event details, server security settings, trusted-member lists, and event logs used by moderation and anti-nuke features.
- **Feature settings and activity:** Saved server and user preferences, leveling records, tickets, music or voice settings, and other data needed to provide a feature.
- **AI conversation data:** If AI features are enabled and used, prompts and relevant recent conversation context are sent to Groq's API to generate a response. Zyven stores a limited recent conversation history and AI preferences so replies can continue in context. Users can clear their saved conversation for a channel with the AI clear command; server administrators can disable automatic AI replies.

## How information is used

Zyven processes data to respond to commands, provide configured server features, enforce administrator-selected moderation and security rules, manage roles, maintain saved settings and progress, operate music and AI functions, troubleshoot errors, and prevent abuse.

## Storage and service providers

Bot settings and feature records are stored in a local SQLite database on the operator's host and, when configured, mirrored to MongoDB for persistence and recovery. The bot keeps database snapshots for recovery; a recently deleted item may remain in a backup until that snapshot is replaced or removed. The bot operator and its hosting and database providers may therefore process stored information.

Zyven communicates with Discord to receive permitted events and perform bot actions. If enabled or used, prompts are sent to Groq for AI responses, and music searches or playback requests are sent to the Lavalink service configured by the operator. Optional external services used by a configured feature may also process the information needed for that feature, under their own policies and terms.

## Retention and deletion

There is no single retention period for every type of data. Settings and feature records may remain while needed to provide the feature or until they are cleared by a user, server administrator, or bot operator. Some records may be included in database recovery snapshots until those snapshots are replaced or removed. Discord channel logs are controlled by the server's administrators and Discord's own retention and deletion features.

For a privacy question or deletion request about data stored by the bot, contact the operators through the [Zyven support server](https://discord.gg/gm6pAGpNGu). Include the relevant Discord user or server ID and identify the feature or record. For message logs posted in a server channel, contact that server's administrators as well. Limited information may need to be retained for security, abuse prevention, backups, or legal obligations.

## Security

The operator uses measures intended to protect bot data, but security also depends on the hosting and database configuration. No online service or data transmission can be guaranteed completely secure.

## Changes and contact

This policy may change as Zyven's features or data practices change. The current version will be available at this URL. For privacy questions, contact the Zyven operators through the [support server](https://discord.gg/gm6pAGpNGu).

---

This policy describes the bot's current code and configured integrations. Third-party providers are governed by their own privacy policies and terms.
