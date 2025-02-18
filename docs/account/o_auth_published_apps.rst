OAuth Published App
===================
.. py:class:: OAuthPublishedAppsAPI

    These APIs enable administrators to view all the available published OAuth applications in Databricks.
    Administrators can add the published OAuth applications to their account through the OAuth Published App
    Integration APIs.

    .. py:method:: list( [, page_size, page_token])

        Get all the published OAuth apps.
        
        Get all the available published OAuth apps in Databricks.
        
        :param page_size: int (optional)
          The max number of OAuth published apps to return.
        :param page_token: str (optional)
          A token that can be used to get the next page of results.
        
        :returns: Iterator over :class:`PublishedAppOutput`
        