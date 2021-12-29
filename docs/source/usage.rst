Using OneDrive on ByteSpeed CLaSS
=====

You can do the following in OneDrive
------------

To use Lumache, first install it using pip:

*	Open and edit files and folders that you store in OneDrive. Content that is stored in OneDrive is specific to you. Other users cannot access your content unless you choose to share it.

*	Upload and download files between your local computer and OneDrive. Any changes that you make to your files and folders in OneDrive during a streaming session are automatically backed up and synchronized. They are available to you when you sign in to your OneDrive account and access OneDrive outside of your streaming session.

*	When you are working in an application, you can access your files and folders that are stored in OneDrive. Choose File, Open from the application interface and browse to the file or folder that you want to open. To save your changes in a file to OneDrive, choose **File, Save** from the application and browse to the location in OneDrive where you want to save the file.

*	You can also access OneDrive by choosing **My Files** from the top left of the AppStream toolbar.


Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

