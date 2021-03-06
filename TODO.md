## List of todo's in priority order:

- [x] Admins
  - [x] Only the creator with master ID can use `/admin` and `/unadmin` command.
  - [x] `/admin` to make an user admin (by reply or mention).
  - [x] `/unadmin` to remove an user from admin list.
  - [x] Admins cannot be warned or banned.
  - [x] `/admin` command should clear all warnings of the user
  - [x] `/admin` command on banned users should throw a warning and cancle the command.
- [x] Warnings
  - [x] `/warn <reason>` command to warn users.
  - [x] Warned message get deleted automatically.
  - [x] Auto warn and remove forwarded messages if they're not from specified channel(s).
  - [x] Auto warn and remove Telegram links if they're not one specified groups or the channel.
  - [x] `/getwarns` get the list of warns with their reason for a user (by reply or mention).
  - [x] `/unwarn` to remove the latest warn from a user (by reply or mention).
  - [x] `/nowarns` to clear all warns (by reply or mention).
  - [x] 3 warns automatically bans the user.
  - [x] Synchronize warns across the groups.
  - [x] All warning commands should first check if there's warnings.
- [x] Bans
  - [x] `/ban <reason>` command to ban users.
  - [x] Remove the message which was replied with a ban command.
  - [X] Ban all bots when they're added (unless added by admin).
  - [x] `/unban <id>` unban a user.
  - [x] Synchronize ban across the groups.
- [x] ~~All command be available with both `!` and `/`.~~
- [x] Auto remove commands if they're not sent by admins.
- [x] Auto remove joining messages.
- [x] Use first name instead of username for link.
- [x] Commands work with username too.
- [x] Commands should tell which admin sent the command.
- [ ] Ban and remove Arabic/Russian/Indian text.
- [x] `/report` and `@admin` to report a message to admins.
- [x] ~~`/link` to show the link of current group.~~
- [x] `/groups` to show the list of groups' link.
- [ ] custom commands -- seeing a defined command, bot should reply with static text, read from db. Can be used to implement `/channel` and `/rules`.
- [x] ~~`/channel` to show the channel link.~~
- [x] `/staff` to show the list of admins.
- [x] ~~`/rules` to show rules. Only admins can use this command.~~
- [x] `/start`, showing basic info about the bot, `/help` explaining all the commands (probably grouped by normie commands, admin commands and custom commands) (I think it's best to implement `/start` and `/help` after we're done with other stuff, so we don't have to revisit them).
