Ending your Session
=====

When you are done using AppStream make sure to save any work, then ByteSpeed recommends that you close the tab in which you have AppStream open. This then will terminate your session after 5 minutes and give time for any pending file syncs to happen between AppStream and your cloud storage.


Idle Disconnect
------------

AppStream will automatically disconnect idle users after 15 minutes *(Default)*. A notification will appear informing you that you are about to be disconnected due to inactivity. If you reconnect in the next 5 minutes you will be reconnected to the same streaming session, otherwise, you will start a new streaming session.

Users are considered idle when they stop providing keyboard or mouse input during their streaming session. File uploads and downloads, audio in, audio out, and pixels changing do not qualify as user activity.

.. image:: _static/inactivity_timeout.png

Max Session Duration
------------

AppStream session length is capped at 60 minutes *(Default)*. If you are still connected five minutes before this limit is reached, you are prompted to save any open documents before being disconnected. After this time elapses, the instance is terminated and replaced by a new instance.


Ending Fozen Session or for Testing
------------

ByteSpeed only recommends ending you session manually if you are experiencing issues with your instance and plan on start a new session right away or if you have no saved files to sync.

1. Select Profile from the navigation bar

    .. image:: _static/navbar_profile.png
	   :scale: 50%

2. Select **End session** to logout

    .. image:: _static/navbar_endsession.png