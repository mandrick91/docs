Organizing Conversations
======================================
_____

Channel Types
-------------------------------------
Channels are used to organize conversations across different topics. There are three types of channels: Public Channels, Private Channels, and Direct Messages.

Public Channels
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Public Channels are open to everyone on a team. New team members are automatically added to two Public Channels when they sign up: Town Square and Off-Topic.

Private Channels
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Private Channels are for sensitive topics and are only visible to select team members. Any member of a Private Channel can add additional members. Channel members can choose to leave at any time, but only the channel owner or `Team Admin <http://docs.mattermost.com/help/getting-started/managing-members.html#user-roles>`_ can remove other members.

Direct Messages and Group Messages
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Direct Messages are for conversations between two people. Group Messages are Direct Messages that have conversations among three or more people. Both are visible only to the people involved.

Use a Direct Message when you want a private conversation with one other person. Use a Group Message when you want to quickly set up a conversation with up to seven other participants. If you want more than that, you must create a Private Channel.

If your System Administrator has allowed it, you can start a Direct Message or a Group Message with people on other teams, not just your own.

There is also an online status indicator next to the names in the Direct Message list. It displays: online (active browser), away (no browser activity for 5 minutes), do not disturb (disabled desktop and push notifications) and offline (browser closed).

Managing Channels
-----------------------------------------
Channels can be created, joined, renamed, left and archived.

Creating a Channel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Create a new Public Channel or Private Channel by selecting the **+** symbol next to the *Channels* or *Private Channels* header on the left hand side. To start a direct message thread, click **More** at the bottom of the *Direct Messages* list to view a list of team members you can message.

Anyone can create Public Channels or Private Channels, unless the System Administrator has `restricted the permissions <https://docs.mattermost.com/administration/config-settings.html#enable-public-channel-creation-for>`_.

Joining a Channel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Click **More** at the bottom of the *Channels* list to view a list of Public Channels you can join. To join a Private Channel you need to be added by a member of that channel.

Adding Members to a Channel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Click the channel name at the top of the center pane to access the drop-down menu, then click **Add Members**. Any member of a channel can add new members by clicking **Add** next to a user's name. Users already added to the channel will not appear in this modal.

Removing Members from a Channel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Click the channel name at the top of the center pane to access the drop-down menu, then click **Manage Members**. Any member of a channel can remove other members by clicking **Remove** next to a user's name.

Naming a Channel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Channels can be identified by:

1. Channel display name: This is the channel name appearing in the Mattermost user interface. Click the channel name at the top of the center pane to access the drop-down menu, then click **Rename Channel**. Anyone can rename the channels they belong to, unless the System Administrator has `restricted the permissions <https://docs.mattermost.com/administration/config-settings.html#enable-public-channel-renaming-for>`_.
2. Channel handle: This is part of the channel URL. You may also change the channel handle when renaming a channel, but changing channel handle may break existing links.

For example, for the following channel: https://pre-release.mattermost.com/core/channels/ux-design

- Channel display name: ``UX Design``
- Channel handle: ``ux-design`` 

Leaving a Channel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Click the channel name at the top of the center pane to access the drop-down menu, then click **Leave Channel**. Any team member who leaves a Private Channel must be re-added by a channel member if they wish to rejoin. Team members will not receive mention notifications from channels of which they are not members.

Archiving a Channel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Click the channel name at the top of the center pane to access the drop-down menu, then click **Archive Channel**. Anyone can archive the Public Channels or Private Channels they belong to, unless the System Administrator has `restricted the permissions <https://docs.mattermost.com/administration/config-settings.html#id2>`_.

When a channel is archived, it is removed from the user interface, but a copy exists on the server in case it is needed for audit reasons later. Because of this, the URL of a newly created channel cannot be the same URL name as an archived channel.

Converting Public Channels to Private
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Click the channel name at the top of the center pane to access the drop-down menu, then click **Convert to Private Channel**. Team and System Admins have the ability to convert public channels to private channels. When a channel is converted, history and membership are preserved. Membership in a private channel is by invitation only. Publicly shared files remain accessible to anyone with the link. 

Note that conversion of private channels to public channels is not supported in the user interface given security concerns of sharing private channel history; however, this function is available via `CLI command <https://docs.mattermost.com/administration/command-line-tools.html#platform-channel-modify>`_.

Favoriting a Channel
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Favorite channels are a great way to organize your sidebar by choosing which Channels, Private Channels, and Direct Messages are most important to you.

To mark a channel as a favorite, simply open the channel and then:

**On desktop:** At the top of the page, click on the star next to the channel name

    .. image:: ../../images/favorite_channels_desktop.png
       :scale: 35


**On mobile:** Open the dropdown list by the channel name, and select "Add to Favorites"

This will add the channel to a "Favorites" section in the top of the sidebar, so it's easy to access. To remove a channel from the "Favorites" section, click the star again on desktop or select "Remove from Favorites" on mobile.

    .. image:: ../../images/favorite_channels_sidebar.png
       :scale: 35
