# Table of contents

* [Rocket.Chat Developer](README.md)

## Guides

* [Developer Guides](guides/developer/README.md)
  * [Contributors instant start on Gitpod](guides/developer/contributors-instant-start-on-gitpod.md)
  * [Quick Start on Linux](guides/developer/quick-start.md)
  * [Developing on Windows 10](guides/developer/developing-on-windows-10.md)
  * [Development Workflow](guides/developer/branches-and-releases.md)
  * [Code Styleguide](guides/developer/code-styleguide/README.md)
    * [CSS Styleguide](guides/developer/code-styleguide/less.md)
  * [Internationalization](guides/developer/internationalization.md)
  * [Mobile apps](guides/developer/mobile-apps/README.md)
    * [Whitelabeling mobile apps](guides/developer/mobile-apps/whitelabeling-mobile-apps.md)
    * [Supporting SSL for development on Rocket.Chat](guides/developer/mobile-apps/supporting-ssl.md)
    * [Analytics & Data Usage](guides/developer/mobile-apps/analytics.md)
  * [UI and Theming](guides/developer/ui-and-theming/README.md)
    * [UI Components](guides/developer/ui-and-theming/components.md)
    * [Custom Themes](guides/developer/ui-and-theming/themes.md)
    * [UI Colors](guides/developer/ui-and-theming/colors.md)
  * [Deeplink](guides/developer/deeplink.md)
  * [Testing](guides/developer/testing.md)
  * [Deprecation](guides/developer/deprecation.md)
  * [Embedded Layout](guides/developer/embedded-layout.md)
  * [Iframe Integration](guides/developer/iframe-integration/README.md)
    * [What is iframe auth?](guides/developer/iframe-integration/authentication/README.md)
      * [Testing the iFrame Authentication](guides/developer/iframe-integration/authentication/testing-the-iframe-authentication.md)
    * [Iframe Events](guides/developer/iframe-integration/events.md)
    * [Iframe integration: Sending commands](guides/developer/iframe-integration/commands.md)
  * [Two Factor Authentication](guides/developer/two-factor.md)
  * [Troubleshooting](guides/developer/troubleshooting.md)
* [Bots Guides](guides/bots/README.md)
  * [Bot Glossary](guides/bots/bot-glossary.md)
  * [Create and run a Bot](guides/bots/create-and-run-a-bot/README.md)
    * [Run a Hubot bot](guides/bots/create-and-run-a-bot/hubot-bot.md)
    * [Run a Botkit Bot](guides/bots/create-and-run-a-bot/botkit-bot.md)
    * [Run a Rocket.Chat SDK Bot](guides/bots/create-and-run-a-bot/rocketchat-sdk-bot.md)
    * [Run a Botpress Bot](guides/bots/create-and-run-a-bot/botpress-bot.md)
    * [Run a Rasa Bot](guides/bots/create-and-run-a-bot/rasa-bot.md)
  * [Running a bBot Bot](guides/bots/running-a-bbot-bot.md)
  * [Configure bot environments](guides/bots/configure-bot-environment.md)
  * [Bots Architecture](guides/bots/bots-architecture.md)
  * [Create a Bot User](guides/bots/create-bot-users.md)
  * [Running a Rasa Bot](guides/bots/running-a-rasa-bot.md)
  * [Running a Hubot bot](guides/bots/running-a-hubot-bot.md)

## API

* [Schema Definition](api/schema-definition/README.md)
  * [User](api/schema-definition/user.md)
  * [Room](api/schema-definition/the-room-object.md)
  * [Subscriptions](api/schema-definition/subscriptions.md)
  * [Message](api/schema-definition/the-message-object.md)
* [Schema Definition v2 \(Draft\)](api/schema-definition-v2/README.md)
  * [Events](api/schema-definition-v2/events/README.md)
    * [EventContext](api/schema-definition-v2/events/eventcontext.md)
    * [IEvent](api/schema-definition-v2/events/event/README.md)
      * [EventContext](api/schema-definition-v2/events/event/event-context.md)
      * [EventTypeDescriptor](api/schema-definition-v2/events/event/event-type-descriptor.md)
      * [EventMessageTypeDescriptor](api/schema-definition-v2/events/event/eventmessagetypedescriptor.md)
      * [EventDataDefinition](api/schema-definition-v2/events/event/event-data-definition/README.md)
        * [IEventDataEmpty](api/schema-definition-v2/events/event/event-data-definition/i-event-data-empty.md)
        * [IEventDataUpdate](api/schema-definition-v2/events/event/event-data-definition/i-event-data-update.md)
    * [IRoomEvent](api/schema-definition-v2/events/iroomevent/README.md)
      * [RoomEventTypeDescriptor](api/schema-definition-v2/events/iroomevent/roomeventtypedescriptor.md)
      * [RoomEventDataDefinition](api/schema-definition-v2/events/iroomevent/room-event-data-definition/README.md)
        * [IRoomEventDataRoom](api/schema-definition-v2/events/iroomevent/room-event-data-definition/i-room-event-data-room.md)
        * [IRoomEventDataMessage](api/schema-definition-v2/events/iroomevent/room-event-data-definition/i-room-event-data-message.md)
  * [IFederationInfo](api/schema-definition-v2/ifederationinfo.md)
  * [IMessage](api/schema-definition-v2/imessage.md)
  * [IRoom](api/schema-definition-v2/room.md)
  * [IUser](api/schema-definition-v2/user.md)
* [Realtime API](api/realtime-api/README.md)
  * [Method Calls](api/realtime-api/method-calls/README.md)
    * [Archive Rooms](api/realtime-api/method-calls/archive-rooms.md)
    * [Create Channels](api/realtime-api/method-calls/create-channels.md)
    * [Create Direct Message](api/realtime-api/method-calls/create-direct-message.md)
    * [Create Private Groups](api/realtime-api/method-calls/create-private-groups.md)
    * [Delete Message](api/realtime-api/method-calls/delete-message.md)
    * [Delete Rooms](api/realtime-api/method-calls/delete-rooms.md)
    * [End-to-End Encryption API](api/realtime-api/method-calls/e2e/README.md)
      * [Fetch My Keys](api/realtime-api/method-calls/e2e/e2e.fetch-my-keys.md)
      * [Get Users of Room Without Key](api/realtime-api/method-calls/e2e/e2e.get-users-of-room-without-key.md)
      * [Set Room Key ID](api/realtime-api/method-calls/e2e/e2e.set-room-key-id.md)
      * [Set User Public and Private Keys](api/realtime-api/method-calls/e2e/e2e.set-user-public-and-pivate-keys.md)
      * [Update Group Key](api/realtime-api/method-calls/e2e/e2e.update-group-key.md)
    * [Favoriting Rooms](api/realtime-api/method-calls/favoriting-rooms.md)
    * [Get Permissions](api/realtime-api/method-calls/get-permissions.md)
    * [Get Public Settings](api/realtime-api/method-calls/get-public-settings.md)
    * [Get Room Roles](api/realtime-api/method-calls/get-room-roles.md)
    * [Get Rooms](api/realtime-api/method-calls/get-rooms.md)
    * [Get Subscriptions](api/realtime-api/method-calls/get-subscriptions.md)
    * [Get User Roles](api/realtime-api/method-calls/get-user-roles.md)
    * [Hiding Rooms](api/realtime-api/method-calls/hiding-rooms.md)
    * [Joining Channels](api/realtime-api/method-calls/joining-channels.md)
    * [Leaving Rooms](api/realtime-api/method-calls/leaving-rooms.md)
    * [List Custom Emoji](api/realtime-api/method-calls/list-custom-emoji.md)
    * [Load History](api/realtime-api/method-calls/load-history.md)
    * [Login](api/realtime-api/method-calls/login.md)
    * [Logout](api/realtime-api/method-calls/logout.md)
    * [Notify Room Stream](api/realtime-api/method-calls/notify-room-stream.md)
    * [Opening Rooms](api/realtime-api/method-calls/opening-rooms.md)
    * [Pin Message](api/realtime-api/method-calls/pin-message.md)
    * [Register User](api/realtime-api/method-calls/register-user.md)
    * [Save Room Settings](api/realtime-api/method-calls/save-room-settings.md)
    * [Send Message](api/realtime-api/method-calls/send-message.md)
    * [Set Reaction](api/realtime-api/method-calls/set-reaction.md)
    * [Spotlight \(search\)](api/realtime-api/method-calls/spotlight-search.md)
    * [Star Message](api/realtime-api/method-calls/star-message.md)
    * [Unarchive Rooms](api/realtime-api/method-calls/unarchive-rooms.md)
    * [Unpin Message](api/realtime-api/method-calls/unpin-message.md)
    * [Update Message](api/realtime-api/method-calls/update-message.md)
    * [User Presence](api/realtime-api/method-calls/user-presence.md)
  * [Two Factor Authentication](api/realtime-api/2fa.md)
  * [Livechat Realtime API](api/realtime-api/livechat-api/README.md)
    * [livechat:getInitialData](api/realtime-api/livechat-api/getinitialdata.md)
    * [livechat:registerGuest](api/realtime-api/livechat-api/registerguest.md)
    * [livechat:sendOfflineMessage](api/realtime-api/livechat-api/sendofflinemessage.md)
    * [sendMessageLivechat](api/realtime-api/livechat-api/sendmessagelivechat.md)
    * [stream-livechat-room](api/realtime-api/livechat-api/streamlivechatroom.md)
  * [Subscriptions](api/realtime-api/subscriptions/README.md)
    * [stream-notify-all](api/realtime-api/subscriptions/stream-notify-all.md)
    * [stream-notify-logged](api/realtime-api/subscriptions/stream-notify-logged.md)
    * [stream-notify-room-users](api/realtime-api/subscriptions/stream-notify-room-users.md)
    * [stream-notify-room](api/realtime-api/subscriptions/stream-notify-room.md)
    * [stream-notify-user](api/realtime-api/subscriptions/stream-notify-user.md)
    * [stream-room-messages](api/realtime-api/subscriptions/stream-room-messages.md)
* [REST API](api/rest-api/README.md)
  * [Avatars](api/rest-api/avatars.md)
  * [Methods](api/rest-api/methods/README.md)
    * [Assets](api/rest-api/methods/assets/README.md)
      * [Set Asset](api/rest-api/methods/assets/setasset.md)
      * [Unset Asset](api/rest-api/methods/assets/unsetasset.md)
    * [Authentication](api/rest-api/methods/authentication/README.md)
      * [Login with Facebook](api/rest-api/methods/authentication/facebook.md)
      * [Logout](api/rest-api/methods/authentication/logout.md)
      * [Login](api/rest-api/methods/authentication/login.md)
      * [Login with Twitter](api/rest-api/methods/authentication/twitter.md)
      * [Me](api/rest-api/methods/authentication/me.md)
      * [Login with Google](api/rest-api/methods/authentication/google.md)
    * [Auto Translate](api/rest-api/methods/autotranslate/README.md)
      * [Get Supported Languages](api/rest-api/methods/autotranslate/getsupportedlanguages.md)
      * [Save Settings](api/rest-api/methods/autotranslate/savesettings.md)
      * [Translate Message](api/rest-api/methods/autotranslate/translatemessage.md)
    * [Commands](api/rest-api/methods/commands/README.md)
      * [Get](api/rest-api/methods/commands/get.md)
      * [List](api/rest-api/methods/commands/list.md)
      * [Preview](api/rest-api/methods/commands/preview.md)
      * [Run](api/rest-api/methods/commands/run.md)
    * [Channels](api/rest-api/methods/channels/README.md)
      * [Channel Add All](api/rest-api/methods/channels/addall.md)
      * [Channel Add Leader](api/rest-api/methods/channels/addleader.md)
      * [Channel Add Moderator](api/rest-api/methods/channels/addmoderator.md)
      * [Channel Add Owner](api/rest-api/methods/channels/addowner.md)
      * [Channel Anonymous Read](api/rest-api/methods/channels/anonymousread.md)
      * [Channel Archive](api/rest-api/methods/channels/archive.md)
      * [Channel Close](api/rest-api/methods/channels/close.md)
      * [Channel Counters](api/rest-api/methods/channels/counters.md)
      * [Channel Create](api/rest-api/methods/channels/create.md)
      * [Channel Delete](api/rest-api/methods/channels/delete.md)
      * [Channel Files](api/rest-api/methods/channels/files.md)
      * [Channel History](api/rest-api/methods/channels/history.md)
      * [Channel Info](api/rest-api/methods/channels/info.md)
      * [Channel Invite](api/rest-api/methods/channels/invite.md)
      * [Channel Join](api/rest-api/methods/channels/join.md)
      * [Channel Kick](api/rest-api/methods/channels/kick.md)
      * [Channel Leave](api/rest-api/methods/channels/leave.md)
      * [Channel List Joined](api/rest-api/methods/channels/list-joined.md)
      * [Channel List](api/rest-api/methods/channels/list.md)
      * [Channel Members List](api/rest-api/methods/channels/members.md)
      * [Channel messages](api/rest-api/methods/channels/messages.md)
      * [Channel Moderators List](api/rest-api/methods/channels/moderators.md)
      * [Channel Online](api/rest-api/methods/channels/online.md)
      * [Channel Open](api/rest-api/methods/channels/open.md)
      * [Channel Remove Leader](api/rest-api/methods/channels/removeleader.md)
      * [Channel Remove Moderator](api/rest-api/methods/channels/removemoderator.md)
      * [Channel Remove Owner](api/rest-api/methods/channels/removeowner.md)
      * [Channel Rename](api/rest-api/methods/channels/rename.md)
      * [Channel Roles](api/rest-api/methods/channels/roles.md)
      * [Channel Set Announcement](api/rest-api/methods/channels/setannouncement.md)
      * [Channel Set Custom Fields](api/rest-api/methods/channels/setcustomfields.md)
      * [Channel Set Default](api/rest-api/methods/channels/setdefault.md)
      * [Channel Set Description](api/rest-api/methods/channels/setdescription.md)
      * [Channel Set Join Code](api/rest-api/methods/channels/setjoincode.md)
      * [Channel Set Purpose](api/rest-api/methods/channels/setpurpose.md)
      * [Channel Set Read Only](api/rest-api/methods/channels/setreadonly.md)
      * [Channel Set Topic](api/rest-api/methods/channels/settopic.md)
      * [Channel Set Type](api/rest-api/methods/channels/settype.md)
      * [Channel Unarchive](api/rest-api/methods/channels/unarchive.md)
      * [Get all the mentions of a channel](api/rest-api/methods/channels/getallusermentionsbychannel.md)
      * [Get Integrations](api/rest-api/methods/channels/getintegrations.md)
    * [Chat](api/rest-api/methods/chat/README.md)
      * [Delete](api/rest-api/methods/chat/delete.md)
      * [React](api/rest-api/methods/chat/react.md)
      * [Update](api/rest-api/methods/chat/update.md)
      * [Report Message](api/rest-api/methods/chat/reportmessage.md)
      * [Follows Message](api/rest-api/methods/chat/followmessage.md)
      * [Get Message](api/rest-api/methods/chat/getmessage.md)
      * [Get Channel Threads](api/rest-api/methods/chat/getthreadslist.md)
      * [Get Deleted Messages](api/rest-api/methods/chat/getdeletedmessages.md)
      * [Get Discussions of A Room](api/rest-api/methods/chat/getdiscussions.md)
      * [Get Mentioned Messages](api/rest-api/methods/chat/getmentionedmessages.md)
      * [Get Message Read Receipts](api/rest-api/methods/chat/getmessagereadreceipts.md)
      * [Get Pinned Messages](api/rest-api/methods/chat/getpinnedmessages.md)
      * [Get Snippeted Message By Id](api/rest-api/methods/chat/getsnippetedmessagebyid.md)
      * [Get Snippeted Messages](api/rest-api/methods/chat/getsnippetedmessages.md)
      * [Get Starred Messages](api/rest-api/methods/chat/getstarredmessages.md)
      * [Get Thread Messages](api/rest-api/methods/chat/getthreadmessages.md)
      * [Ignore User](api/rest-api/methods/chat/ignoreuser.md)
      * [Pins Message](api/rest-api/methods/chat/pinmessage.md)
      * [Post Message](api/rest-api/methods/chat/postmessage.md)
      * [Search](api/rest-api/methods/chat/search.md)
      * [Send Message](api/rest-api/methods/chat/sendmessage.md)
      * [Star Message](api/rest-api/methods/chat/starmessage.md)
      * [Sync Thread List](api/rest-api/methods/chat/syncthreadslist.md)
      * [Sync Thread Messages](api/rest-api/methods/chat/syncthreadmessages.md)
      * [Unfollow Message](api/rest-api/methods/chat/unfollowmessage.md)
      * [Unpins Message](api/rest-api/methods/chat/unpinmessage.md)
      * [Unstar Message](api/rest-api/methods/chat/unstarmessage.md)
    * [Custom Emoji](api/rest-api/methods/emoji-custom/README.md)
      * [Create](api/rest-api/methods/emoji-custom/create.md)
      * [Delete](api/rest-api/methods/emoji-custom/delete.md)
      * [List](api/rest-api/methods/emoji-custom/list.md)
      * [Update](api/rest-api/methods/emoji-custom/update.md)
    * [Custom Sounds](api/rest-api/methods/custom-sounds/README.md)
      * [Custom Sounds List](api/rest-api/methods/custom-sounds/list.md)
    * [Custom User Status](api/rest-api/methods/custom-user-status/README.md)
      * [Custom User Status List](api/rest-api/methods/custom-user-status/list.md)
    * [Groups](api/rest-api/methods/groups/README.md)
      * [Group Online](api/rest-api/methods/groups/group-online.md)
      * [Get Integrations](api/rest-api/methods/groups/getintegrations.md)
      * [Group Add All](api/rest-api/methods/groups/addall.md)
      * [Group Add Leader](api/rest-api/methods/groups/addleader.md)
      * [Group Add Moderator](api/rest-api/methods/groups/addmoderator.md)
      * [Group Add Owner](api/rest-api/methods/groups/addowner.md)
      * [Group Archive](api/rest-api/methods/groups/archive.md)
      * [Group Close](api/rest-api/methods/groups/close.md)
      * [Group Counters](api/rest-api/methods/groups/counters.md)
      * [Group Create](api/rest-api/methods/groups/create.md)
      * [Group Delete](api/rest-api/methods/groups/delete.md)
      * [Group History](api/rest-api/methods/groups/history.md)
      * [Group Info](api/rest-api/methods/groups/info.md)
      * [Group Invite](api/rest-api/methods/groups/invite.md)
      * [Group Kick](api/rest-api/methods/groups/kick.md)
      * [Group Leave](api/rest-api/methods/groups/leave.md)
      * [Group List All](api/rest-api/methods/groups/listall.md)
      * [Group List](api/rest-api/methods/groups/list.md)
      * [Group Members](api/rest-api/methods/groups/members.md)
      * [Group messages](api/rest-api/methods/groups/messages.md)
      * [Group Moderators List](api/rest-api/methods/groups/moderators.md)
      * [Group Open](api/rest-api/methods/groups/open.md)
      * [Group Remove Leader](api/rest-api/methods/groups/removeleader.md)
      * [Group Remove Moderator](api/rest-api/methods/groups/removemoderator.md)
      * [Group Remove Owner](api/rest-api/methods/groups/removeowner.md)
      * [Group Rename](api/rest-api/methods/groups/rename.md)
      * [Group Set Announcement](api/rest-api/methods/groups/setannouncement.md)
      * [Group Set Custom Fields](api/rest-api/methods/groups/setcustomfields.md)
      * [Group Set Description](api/rest-api/methods/groups/setdescription.md)
      * [Group Set Purpose](api/rest-api/methods/groups/setpurpose.md)
      * [Group Set Read Only](api/rest-api/methods/groups/setreadonly.md)
      * [Group Set Topic](api/rest-api/methods/groups/settopic.md)
      * [Group Set Type](api/rest-api/methods/groups/settype.md)
      * [Group Unarchive](api/rest-api/methods/groups/unarchive.md)
      * [Groups Files](api/rest-api/methods/groups/files.md)
      * [Groups Roles](api/rest-api/methods/groups/roles.md)
    * [Invite](api/rest-api/methods/invites/README.md)
      * [Find or Create Invite](api/rest-api/methods/invites/findorcreateinvite.md)
      * [List Invites](api/rest-api/methods/invites/listinvites.md)
      * [Remove Invite](api/rest-api/methods/invites/removeinvite.md)
      * [Use Invite Token](api/rest-api/methods/invites/useinvitetoken.md)
      * [Validate Invite Token](api/rest-api/methods/invites/validateinvitetoken.md)
    * [Integration](api/rest-api/methods/integration/README.md)
      * [Create](api/rest-api/methods/integration/create.md)
      * [Get](api/rest-api/methods/integration/get.md)
      * [History](api/rest-api/methods/integration/history.md)
      * [List](api/rest-api/methods/integration/list.md)
      * [Remove](api/rest-api/methods/integration/remove.md)
    * [IM](api/rest-api/methods/im/README.md)
      * [Close](api/rest-api/methods/im/close.md)
      * [Counters](api/rest-api/methods/im/counters.md)
      * [Create](api/rest-api/methods/im/create.md)
      * [Files](api/rest-api/methods/im/files.md)
      * [History](api/rest-api/methods/im/history.md)
      * [List Everyone](api/rest-api/methods/im/list-everyone.md)
      * [List](api/rest-api/methods/im/list.md)
      * [Members](api/rest-api/methods/im/members.md)
      * [Messages Others](api/rest-api/methods/im/messages-others.md)
      * [Messages](api/rest-api/methods/im/messages.md)
      * [Open](api/rest-api/methods/im/open.md)
      * [Set Topic](api/rest-api/methods/im/settopic.md)
    * [Omnichannel](api/rest-api/methods/livechat/README.md)
      * [Average chat duration by department](api/rest-api/methods/livechat/average-chat-duration-by-department.md)
      * [Total service time by department](api/rest-api/methods/livechat/total-service-time-by-department.md)
      * [Average waiting time by department](api/rest-api/methods/livechat/average-waiting-time-by-department.md)
      * [Total of transferred chats by department](api/rest-api/methods/livechat/total-of-transferred-chats-by-department.md)
      * [Agents total service time](api/rest-api/methods/livechat/agents-total-service-time.md)
      * [Agents average service time](api/rest-api/methods/livechat/agents-average-service-time.md)
      * [Total abandoned chats by department](api/rest-api/methods/livechat/total-abandoned-chats-by-department.md)
      * [Percentage of abandoned chats by department](api/rest-api/methods/livechat/percentage-of-abandoned-chats-by-department.md)
      * [Agents available for service time](api/rest-api/methods/livechat/agents-available-for-service-time.md)
      * [Agent Info](api/rest-api/methods/livechat/agent.md)
      * [Appearance](api/rest-api/methods/livechat/appearance.md)
      * [Config](api/rest-api/methods/livechat/config.md)
      * [Custom Field](api/rest-api/methods/livechat/custom-fields.md)
      * [Department](api/rest-api/methods/livechat/department.md)
      * [Inquiries List](api/rest-api/methods/livechat/inquiries.md)
      * [Integrations Settings](api/rest-api/methods/livechat/integrations-settings.md)
      * [Message](api/rest-api/methods/livechat/message.md)
      * [Office Hours](api/rest-api/methods/livechat/office-hours.md)
      * [Queue](api/rest-api/methods/livechat/queue.md)
      * [Room](api/rest-api/methods/livechat/room.md)
      * [Rooms](api/rest-api/methods/livechat/rooms.md)
      * [SMS Incoming](api/rest-api/methods/livechat/sms-incoming.md)
      * [Transcript](api/rest-api/methods/livechat/transcript.md)
      * [Triggers](api/rest-api/methods/livechat/triggers.md)
      * [Users](api/rest-api/methods/livechat/users.md)
      * [Video Call](api/rest-api/methods/livechat/video-call.md)
      * [Visitors](api/rest-api/methods/livechat/visitor.md)
    * [OAuthApps](api/rest-api/methods/oauthapps/README.md)
      * [Get](api/rest-api/methods/oauthapps/get.md)
      * [List](api/rest-api/methods/oauthapps/list.md)
    * [Miscellaneous](api/rest-api/methods/miscellaneous/README.md)
      * [Directory](api/rest-api/methods/miscellaneous/directory.md)
      * [Info](api/rest-api/methods/miscellaneous/info.md)
      * [Shield SVG](api/rest-api/methods/miscellaneous/shield-svg.md)
      * [Spotlight](api/rest-api/methods/miscellaneous/spotlight.md)
      * [Statistics](api/rest-api/methods/miscellaneous/statistics.md)
      * [Statistics List](api/rest-api/methods/miscellaneous/statistics-list.md)
    * [Permissions](api/rest-api/methods/permissions/README.md)
      * [List All](api/rest-api/methods/permissions/listall.md)
      * [Update](api/rest-api/methods/permissions/update.md)
    * [Push Token](api/rest-api/methods/push/README.md)
      * [Delete](api/rest-api/methods/push/deletepushtoken.md)
      * [Post](api/rest-api/methods/push/push-token.md)
    * [Roles](api/rest-api/methods/roles/README.md)
      * [Role AddUserToRole](api/rest-api/methods/roles/addusertorole.md)
      * [Role Create](api/rest-api/methods/roles/create.md)
      * [Role Get Users In Role](api/rest-api/methods/roles/getusersinrole.md)
      * [Role List](api/rest-api/methods/roles/list.md)
      * [Role Sync](api/rest-api/methods/roles/sync.md)
    * [Rooms](api/rest-api/methods/rooms/README.md)
      * [Save Notification](api/rest-api/methods/rooms/savenotification.md)
      * [Admin Rooms](api/rest-api/methods/rooms/adminrooms.md)
      * [Clean History](api/rest-api/methods/rooms/cleanhistory.md)
      * [Rooms Info](api/rest-api/methods/rooms/info.md)
      * [Get Discussions](api/rest-api/methods/rooms/getdiscussions.md)
      * [Get](api/rest-api/methods/rooms/get.md)
      * [Leave](api/rest-api/methods/rooms/leave.md)
      * [Favorite](api/rest-api/methods/rooms/favorite.md)
      * [Upload](api/rest-api/methods/rooms/upload.md)
      * [Create Discussion](api/rest-api/methods/rooms/creatediscussion.md)
    * [Settings](api/rest-api/methods/settings/README.md)
      * [oAuth](api/rest-api/methods/settings/oauth.md)
      * [Private Settings](api/rest-api/methods/settings/get.md)
      * [Public Settings Get](api/rest-api/methods/settings/public.md)
      * [Service Configurations Get](api/rest-api/methods/settings/service-configuration.md)
      * [Settings Get](api/rest-api/methods/settings/get-by-id.md)
      * [Settings Update](api/rest-api/methods/settings/update.md)
    * [Subscriptions](api/rest-api/methods/subscriptions/README.md)
      * [Get One](api/rest-api/methods/subscriptions/getone.md)
      * [Get](api/rest-api/methods/subscriptions/get.md)
      * [Read](api/rest-api/methods/subscriptions/read.md)
      * [Unread](api/rest-api/methods/subscriptions/unread.md)
    * [Users](api/rest-api/methods/users/README.md)
      * [Create Token](api/rest-api/methods/users/createtoken.md)
      * [Create](api/rest-api/methods/users/create.md)
      * [Delete Own Account](api/rest-api/methods/users/deleteownaccount.md)
      * [Delete](api/rest-api/methods/users/deactivateidle.md)
      * [Delete](api/rest-api/methods/users/delete.md)
      * [Forgot Password](api/rest-api/methods/users/forgotpassword.md)
      * [Generate Personal Access Token](api/rest-api/methods/users/generatepersonalaccesstoken.md)
      * [Get Avatar](api/rest-api/methods/users/getavatar.md)
      * [Get Personal Access Tokens](api/rest-api/methods/users/getpersonalaccesstokens.md)
      * [Get Preferences](api/rest-api/methods/users/get-preferences.md)
      * [Get Presence](api/rest-api/methods/users/getpresence.md)
      * [Get Status](api/rest-api/methods/users/getstatus.md)
      * [Get Username Suggestion](api/rest-api/methods/users/getusernamesuggestion.md)
      * [Info](api/rest-api/methods/users/info.md)
      * [List](api/rest-api/methods/users/list.md)
      * [Regenerate Personal Access Token](api/rest-api/methods/users/regeneratepersonalaccesstoken.md)
      * [Register](api/rest-api/methods/users/register.md)
      * [Register](api/rest-api/methods/users/removeothertokens.md)
      * [Remove Personal Access Token](api/rest-api/methods/users/removepersonalaccesstoken.md)
      * [Request Data Download](api/rest-api/methods/users/requestdatadownload.md)
      * [Reset Avatar](api/rest-api/methods/users/resetavatar.md)
      * [Set Active Status](api/rest-api/methods/users/setactivestatus.md)
      * [Set Avatar](api/rest-api/methods/users/setavatar.md)
      * [Set Preferences](api/rest-api/methods/users/set-preferences.md)
      * [Set Status](api/rest-api/methods/users/setstatus.md)
      * [Update own basic information](api/rest-api/methods/users/updateownbasicinfo.md)
      * [Update](api/rest-api/methods/users/update.md)
      * [Users Presence](api/rest-api/methods/users/presence.md)
    * [Video Conference](api/rest-api/methods/video-conference/README.md)
      * [Update Jitsi Timeout](api/rest-api/methods/video-conference/jitsi-update-timeout.md)
    * [Webdav](api/rest-api/methods/webdav/README.md)
      * [Get My Accounts](api/rest-api/methods/webdav/getmyaccounts.md)
  * [Access Tokens](api/rest-api/personal-access-tokens.md)
  * [Two Factor Authentication](api/rest-api/2fa.md)
  * [Query and Fields](api/rest-api/query-and-fields-info.md)
  * [Pagination](api/rest-api/offset-and-count-and-sort-info.md)
  * [Rate Limiter](api/rest-api/rate-limiter.md)
* [Livechat Widget API](api/livechat-api.md)

## Apps Development

* [Rocket.Chat App](apps-development/getting-started/README.md)
  * [Rocket.Chat App Engine CLI](apps-development/getting-started/rocket.chat-app-engine-cli.md)
  * [Creating an App](apps-development/getting-started/creating-an-example-app.md)
  * [App Submission to the Marketplace](apps-development/getting-started/submitting-app-to-the-marketplace/README.md)
    * [App Submission through CLI](apps-development/getting-started/submitting-app-to-the-marketplace/app-submission-through-cli.md)
    * [Paid App Submission \(through Publisher\)](apps-development/getting-started/submitting-app-to-the-marketplace/paid-app-submission-through-publisher.md)
* [Fundamentals](apps-development/fundamentals/README.md)
  * [App Lifecycle](apps-development/fundamentals/app-lifecycle.md)
  * [Event Interfaces](apps-development/fundamentals/event-interfaces.md)
  * [Scheduler API](apps-development/fundamentals/scheduler-api.md)
* [Recipes](apps-development/recipes/README.md)
  * [Sub-command pattern](apps-development/recipes/sub-command-pattern.md)
  * [Extending Messages](apps-development/recipes/extending-messages.md)
  * [Making HTTP Requests](apps-development/recipes/making-http-requests.md)
  * [Storing User Input](apps-development/recipes/storing-user-input.md)
  * [Registering API endpoints](apps-development/recipes/registering-api-endpoints.md)
* [Slack Compatibility](apps-development/slack-compatibility.md)
* [Permission System](apps-development/permission-system.md)
* [UIKit](apps-development/uikit/README.md)
  * [UIKit building blocks](apps-development/uikit/uikit-building-blocks.md)
  * [Slack Compatibility Layer's unsupported properties](apps-development/uikit/slack-compatibility-layers-unsupported-properties.md)
* [Apps-Engine API Reference](https://rocketchat.github.io/Rocket.Chat.Apps-engine)

## Fuselage

* [Contributing](fuselage/contributing.md)

