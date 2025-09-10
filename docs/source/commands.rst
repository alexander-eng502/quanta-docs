Commands Reference
==================

This page provides detailed information about all Searchify commands, organized by category. Each command includes usage examples and explanations of parameters.

.. _music-commands:

Music Commands
--------------

Searchify provides comprehensive music playback functionality with advanced features like filters and looping.

``/music play``
~~~~~~~~~~~~~~~
Play music from various sources.

**Usage:**
   - ``/music play query:Never Gonna Give You Up`` - Play a song by search term
   - ``/music play query:https://www.youtube.com/watch?v=dQw4w9WgXcQ`` - Play from URL

``/music filter``
~~~~~~~~~~~~~~~~~
Apply audio filters to enhance your music experience.

**Parameters:**
   - ``strength`` (float): Filter intensity from 0.0 to 1.0
      - ``0.0`` = No effect (disable filter)
      - ``0.5`` = Moderate effect
      - ``1.0`` = Maximum effect

**Examples:**
   - ``/music filter strength:0.3`` - Apply light filtering
   - ``/music filter strength:0.8`` - Apply strong filtering
   - ``/music filter strength:0.0`` - Remove all filters

.. tip::
   **What is a float?** A float is a decimal number. You can use values like ``0.1``, ``0.5``, ``0.75``, or ``1.0``.

``/music volume``
~~~~~~~~~~~~~~~~~
Adjust playback volume.

**Parameters:**
   - ``level`` (integer): Volume level from 0 to 100

**Examples:**
   - ``/music volume level:50`` - Set volume to 50%
   - ``/music volume level:100`` - Maximum volume

``/music loop``
~~~~~~~~~~~~~~~
Control track or queue looping.

**Options:**
   - ``off`` - Disable looping
   - ``track`` - Loop current track
   - ``queue`` - Loop entire queue

Other Music Commands
~~~~~~~~~~~~~~~~~~~~
   - ``/music skip`` - Skip to next track
   - ``/music pause`` - Pause playback
   - ``/music resume`` - Resume playback
   - ``/music info`` - Show current track information
   - ``/music track`` - Display track details

Radio Commands
--------------

Listen to online radio stations.

``/radio play``
~~~~~~~~~~~~~~~
Play from online radio stations.

**Usage:**
   - ``/radio play station:BBC Radio 1``
   - ``/radio play station:NPR``

``/radio volume``
~~~~~~~~~~~~~~~~~
Adjust radio volume (same as music volume).

Search & Information Commands
-----------------------------

``/search``
~~~~~~~~~~~
Search the web for information.

**Usage:**
   - ``/search query:Python programming tutorial``
   - ``/search query:weather forecast``

``/wiki search``
~~~~~~~~~~~~~~~~
Search Wikipedia articles.

**Usage:**
   - ``/wiki search topic:Albert Einstein``
   - ``/wiki search topic:Machine Learning``

``/weather search``
~~~~~~~~~~~~~~~~~~~
Get weather information for any location.

**Usage:**
   - ``/weather search location:New York``
   - ``/weather search location:London, UK``

``/translate``
~~~~~~~~~~~~~~
Translate text between languages.

**Usage:**
   - ``/translate text:Hello world target:spanish``
   - ``/translate text:Bonjour target:english``

Entertainment Commands
----------------------

``/meme``
~~~~~~~~~
Get random memes to brighten your day.

``/random joke``
~~~~~~~~~~~~~~~~
Get a random joke.

``/animal`` / ``/catfact`` / ``/dogfact``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Get random animal pictures or facts.

``/rps``
~~~~~~~~
Play Rock Paper Scissors with the bot.

**Usage:**
   - ``/rps choice:rock``
   - ``/rps choice:paper``
   - ``/rps choice:scissors``

``/coinflip``
~~~~~~~~~~~~~
Flip a virtual coin.

Games & Economy
---------------

``/coins daily`` / ``/coins weekly`` / ``/coins monthly``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Claim your daily, weekly, or monthly coin rewards.

``/coins send``
~~~~~~~~~~~~~~~
Send coins to another user.

**Usage:**
   - ``/coins send user:@username amount:100``

``/shop buy`` / ``/shop sell``
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Buy or sell items in the virtual shop.

``/balance``
~~~~~~~~~~~~
Check your current coin balance.

``/inventory``
~~~~~~~~~~~~~~
View your purchased items.

Utility Commands
----------------

``/remind add``
~~~~~~~~~~~~~~~
Set a reminder for yourself.

**Usage:**
   - ``/reminder add time:10m message:Check the oven``
   - ``/reminder add time:2h message:Meeting with team``

**Time formats:**
   - ``s`` = seconds
   - ``m`` = minutes  
   - ``h`` = hours
   - ``d`` = days

``/encode`` / ``/decode``
~~~~~~~~~~~~~~~~~~~~~~~~~
Encode or decode text in various formats.

**Available formats:**
   - ``base64`` - Base64 encoding
   - ``base32`` - Base32 encoding
   - ``hex`` - Hexadecimal encoding
   - ``url`` - URL encoding
   - ``rot13`` - ROT13 cipher

**Examples:**
   - ``/encode base64 text:Hello World``
   - ``/decode base64 text:SGVsbG8gV29ybGQ=``

``/password``
~~~~~~~~~~~~~
Generate a secure random password.

``/webshot``
~~~~~~~~~~~~
Take a screenshot of a website.

**Usage:**
   - ``/webshot url:https://example.com``

Moderation Commands
-------------------

``/blacklist add``
~~~~~~~~~~~~~~~~~~
Blacklist a user from using the bot.

**Parameters:**
   - ``user_id`` (required): The Discord user ID to blacklist
   - ``reason`` (optional): Reason for blacklisting
   - ``duration`` (optional): How long the blacklist lasts
   - ``dm_user`` (optional): Whether to send a DM to the user

**Usage:**
   - ``/blacklist add user_id:123456789 reason:Spam``

``/blacklist remove``
~~~~~~~~~~~~~~~~~~~~~
Remove a user from the blacklist.

``/blacklist list``
~~~~~~~~~~~~~~~~~~~
View all blacklisted users.

Information Commands
--------------------

``/userinfo``
~~~~~~~~~~~~~
Get detailed information about a user.

**Usage:**
   - ``/userinfo user:@username``

``/guildinfo``
~~~~~~~~~~~~~~
Get information about the current server.

``/botinfo``
~~~~~~~~~~~~
Display information about Searchify.

``/ping``
~~~~~~~~~
Check bot latency and response time.

Tag System
----------

Create custom text shortcuts for your server.

``/tag add``
~~~~~~~~~~~~
Create a new tag.

**Usage:**
   - ``/tag add name:rules content:Please follow our server rules!``

``/tag get``
~~~~~~~~~~~~
Retrieve a tag's content.

**Usage:**
   - ``/tag get name:rules``

``/tag list``
~~~~~~~~~~~~~
List all available tags.

``/tag delete``
~~~~~~~~~~~~~~~
Delete a tag (requires permissions).

``/tag update``
~~~~~~~~~~~~~~~
Update an existing tag's content.

Getting Help
------------

``/help``
~~~~~~~~~
Display all available commands or get help with a specific command.

**Usage:**
   - ``/help`` - Show all commands
   - ``/help command:music`` - Get help with music commands

.. note::
   If you're still confused about any command, feel free to join our support server or check the bot's response messages for additional guidance.

Troubleshooting
---------------

**Common Issues:**

*Bot not responding to commands:*
   - Ensure the bot has proper permissions
   - Check if the bot is online
   - Try ``/ping`` to test connectivity

*Music not playing:*
   - Make sure you're in a voice channel
   - Check if the bot has permission to join voice channels
   - Verify the music source is accessible

*Commands seem complicated:*
   - Start with simple commands like ``/ping`` or ``/meme``
   - Read the examples provided for each command
   - Remember: float values are just decimal numbers (0.1, 0.5, 1.0)
