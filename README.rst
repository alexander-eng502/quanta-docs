Searchify Documentation
=======================

.. image:: https://img.shields.io/badge/Discord-Bot-7289da?style=for-the-badge&logo=discord&logoColor=white
   :alt: Discord Bot
   :target: https://discord.com/oauth2/authorize?client_id=959784292190416906&permissions=8&scope=bot%20applications.commands

.. image:: https://readthedocs.org/projects/searchify-docs/badge/?version=latest
   :target: https://searchify-docs.readthedocs.io/en/latest/?badge=latest
   :alt: Documentation Status

This repository contains the source code for Searchify's documentation, a comprehensive Discord bot with music, utility, and entertainment features.

🤖 **About Searchify**
-----------------------

Searchify is a powerful Discord bot written in Python that provides:

- **Music & Radio**: Full-featured music player with filters and radio stations
- **Search & Info**: Web search, Wikipedia, weather, translations
- **Entertainment**: Memes, jokes, games, animal facts
- **Economy**: Virtual coin system with shop and rewards
- **Utility**: Reminders, encoding/decoding, user management
- **Moderation**: Blacklist system and server management tools

📚 **Documentation**
--------------------

The full documentation is available at: https://searchify-docs.readthedocs.io/

**Quick Links:**
- `Getting Started <https://searchify-docs.readthedocs.io/en/latest/usage.html>`_
- `Commands Reference <https://searchify-docs.readthedocs.io/en/latest/commands.html>`_
- `Terms of Service <https://searchify-docs.readthedocs.io/en/latest/tos.html>`_

🔗 **Invite Searchify**
-----------------------

Add Searchify to your Discord server: `Invite Link <https://discord.com/oauth2/authorize?client_id=959784292190416906&permissions=8&scope=bot%20applications.commands>`_

📖 **Building Documentation Locally**
--------------------------------------

To build this documentation locally:

1. Clone this repository:
   
   .. code-block:: bash
   
      git clone https://github.com/lol219/searchify-docs.git
      cd searchify-docs

2. Install dependencies:
   
   .. code-block:: bash
   
      pip install -r docs/requirements.txt

3. Build the documentation:
   
   .. code-block:: bash
   
      cd docs
      make html

4. Open ``docs/build/html/index.html`` in your browser

🤝 **Contributing**
-------------------

Contributions to improve the documentation are welcome! Please:

1. Fork this repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

**Areas for improvement:**
- Adding more command examples
- Improving explanations for complex features
- Fixing typos or formatting issues
- Adding screenshots or diagrams

📝 **Documentation Structure**
------------------------------

- ``docs/source/index.rst`` - Main documentation page
- ``docs/source/usage.rst`` - Getting started guide  
- ``docs/source/commands.rst`` - Detailed command reference
- ``docs/source/tos.rst`` - Terms of service
- ``docs/source/conf.py`` - Sphinx configuration

🛠️ **Technical Details**
-------------------------

- **Documentation**: Sphinx with Read the Docs theme
- **Hosting**: Read the Docs
- **Format**: reStructuredText (.rst)
- **Python**: Compatible with Python 3.7+

📧 **Contact**
--------------

- **Developer**: Rander
- **GitHub**: https://github.com/lol219
- **Issues**: Report documentation issues in this repository

📄 **License**
--------------

This documentation is provided as-is for the Searchify Discord bot. See the Terms of Service for usage terms.
