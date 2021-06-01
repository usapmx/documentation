=========================================
Fetch product pictures over Google Images
=========================================

Setup in Google
===============

Create your API Key
-------------------

- Go to `Google Cloud Platform <https://console.developers.google.com/>`__ API & Services page
  to generate Google Custom Search API credentials. Log in with your Google account.

- Select or create an API project to store the credentials if not yet done
  before. Give it an explicit name (e.g. Odoo Images).

- In the credentials section, click on Create Crendentials and select **API Keys**

.. image:: media/google_images_credentials00.png
    :align: center

- Save it, you'll need it for the next step in Odoo !

- Use the search bar to find for *Google Custom Search API* and select it.

.. image:: media/google_images_credentials01.png
    :align: center

- Enable the API.

.. image:: media/google_images_credentials02.png
    :align: center

Create your Search Engine ID
----------------------------

- Go to `Google Programmable Search Engine <https://programmablesearchengine.google.com/>`__ and
  click on Get Started. Log in with your Google account.

.. image:: media/google_images_credentials03.png
    :align: center

- Fill the language and the name of the search engine. Give it an explicit name (e.g. Odoo Images).

.. note::
   Google doesn't allow to create a search engine without having entered at least one specific site
   to search on. You can put any website (e.g. www.google.com) for this step, we will remove it
   later.

- Validate the form by clicking on Create. Then, go to the edition mode of the search engine
  that you created (either by clicking on Control Panel button on the confirmation page or by
  clicking on the name of your Search Engine on the Home page).

- In the basics tab, make sure to enable Image search, SafeSearch and Search the entire web.

.. note::
   Once Search the entire web enabled, you can safely delete the site that you previously entered
   at the previous step.

- Save your **Search Engine Id**.

.. tip::
   You can easily save your Search Engine ID by clicking on the Copy to clipboard button next to it.

Setup in Odoo
=============

- Install the App by checking the option in :menuselection:`Settings --> General Settings`.

- Go to :menuselection:`Settings --> General Settings` and enter your
  **API Key** and **Search Engine ID** in Google Images option.

- The setup is now ready.




