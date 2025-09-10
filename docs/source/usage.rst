Getting Started with Searchify
===============================

This guide will help you set up and start using Searchify in your Discord server.

.. _installation:

Step 1: Invite the Bot
----------------------

1. Click the invite link: `Add Searchify to your server <https://discord.com/oauth2/authorize?client_id=959784292190416906&permissions=8&scope=bot%20applications.commands>`_
2. Select the server where you want to add Searchify
3. Make sure the bot has the necessary permissions (Administrator is recommended for full functionality)
4. Click "Authorize"

.. important::
   You need "Manage Server" permissions to invite bots to a Discord server.

Step 2: Verify Installation
---------------------------

Once invited, test if Searchify is working:

1. Go to any text channel where the bot has permissions
2. Type ``/ping`` and press Enter
3. If you see a response with latency information, the bot is working correctly!

Understanding Slash Commands
----------------------------

Searchify uses Discord's modern slash command system. Here's how to use them:

**Basic Usage:**
   1. Type ``/`` in any text channel
   2. You'll see a list of available commands
   3. Click on a command or continue typing to filter
   4. Fill in the required parameters
   5. Press Enter to execute

**Example:**
   - Type ``/weather search``
   - Fill in ``location:New York``
   - Press Enter to get weather information

.. tip::
   Discord will show you parameter hints as you type. Required parameters are marked, optional ones are not.

Step 3: Essential Commands to Try
---------------------------------

Start with these beginner-friendly commands:

**Test Commands:**
   - ``/ping`` - Check if bot is responding
   - ``/botinfo`` - Learn about Searchify
   - ``/help`` - See all available commands

**Fun Commands:**
   - ``/meme`` - Get a random meme
   - ``/coinflip`` - Flip a coin
   - ``/random joke`` - Get a joke

**Useful Commands:**
   - ``/weather search location:your_city`` - Get weather info
   - ``/translate text:hello target:spanish`` - Translate text
   - ``/search query:your_question`` - Search the web

Understanding Parameters
------------------------

Many commands require parameters (additional information). Here are the common types:

**Text Parameters:**
   - Just type your text: ``query:hello world``
   - Use quotes for complex text: ``query:"hello world"``

**Number Parameters:**
   - Integers (whole numbers): ``amount:100``
   - Floats (decimal numbers): ``strength:0.5``

**User Parameters:**
   - Mention a user: ``user:@username``
   - Or use their ID: ``user:123456789``

**Choice Parameters:**
   - Select from dropdown: ``choice:rock`` (for Rock Paper Scissors)

.. _float-explanation:

What are Float Values?
----------------------

Some commands (like ``/music filter``) use "float" values. Don't worry - it's simpler than it sounds!

**Float = Decimal Number**
   - ``0.0`` = Zero/Off
   - ``0.5`` = Half/Medium
   - ``1.0`` = Full/Maximum
   - You can use any decimal: ``0.1``, ``0.25``, ``0.75``, ``0.9``, etc.

**Examples:**
   - ``/music filter strength:0.0`` - No filter
   - ``/music filter strength:0.3`` - Light filter
   - ``/music filter strength:0.7`` - Strong filter
   - ``/music filter strength:1.0`` - Maximum filter

Setting Up Music
-----------------

Music is one of Searchify's most popular features:

**Prerequisites:**
   1. Join a voice channel first
   2. Make sure the bot can see and join voice channels

**Basic Music Commands:**
   1. ``/music play query:song name`` - Play a song
   2. ``/music volume level:50`` - Adjust volume (0-100)
   3. ``/music pause`` - Pause playback
   4. ``/music resume`` - Resume playback
   5. ``/music skip`` - Skip to next song

**Advanced Features:**
   - ``/music loop track`` - Loop current song
   - ``/music filter strength:0.5`` - Apply audio effects
   - ``/radio play station:BBC Radio 1`` - Play radio

Economy System
---------------

Searchify includes a virtual economy system:

**Getting Started:**
   1. ``/coins daily`` - Claim daily coins
   2. ``/balance`` - Check your balance
   3. ``/shop info`` - See what's available
   4. ``/shop buy item:item_name`` - Purchase items

**Regular Activities:**
   - Claim daily, weekly, and monthly rewards
   - Send coins to friends
   - Buy items from the shop

Permissions Setup
-----------------

For full functionality, ensure Searchify has these permissions:

**Essential Permissions:**
   - Send Messages
   - Use Slash Commands
   - Read Message History
   - Embed Links

**For Music:**
   - Connect (to voice channels)
   - Speak (in voice channels)

**For Moderation:**
   - Manage Messages
   - Kick Members (if using moderation features)

.. warning::
   Without proper permissions, some commands may not work correctly.

Troubleshooting
---------------

**Bot Not Responding:**
   1. Check if bot is online (green status)
   2. Verify bot has message permissions in the channel
   3. Try ``/ping`` to test connectivity
   4. Re-invite bot if problems persist

**Slash Commands Not Showing:**
   1. Wait a few minutes after inviting (commands need to sync)
   2. Try refreshing Discord (Ctrl+R)
   3. Check if bot has "Use Application Commands" permission

**Music Issues:**
   1. Ensure you're in a voice channel
   2. Check bot's voice channel permissions
   3. Try a different song/source
   4. Verify volume isn't set to 0

**Command Seems Complicated:**
   1. Check our :doc:`commands` page for examples
   2. Use ``/help command_name`` for specific help
   3. Start with simpler versions of commands

Getting Help
------------

**Built-in Help:**
   - ``/help`` - List all commands
   - ``/help command_name`` - Get specific command help

**Documentation:**
   - :doc:`commands` - Detailed command reference
   - This usage guide
   - :doc:`tos` - Terms of service

**Still Need Help?**
   If you're still having trouble, the bot's error messages usually provide helpful hints about what went wrong.

Next Steps
----------

Now that you know the basics:

1. Explore the :doc:`commands` page for detailed command information
2. Try different command categories (music, games, utility)
3. Set up tags and reminders for your server
4. Experiment with the economy system

Remember: Searchify is designed to be helpful and user-friendly. Don't be afraid to experiment with different commands! 
