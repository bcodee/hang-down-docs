#######################
How to use it?
#######################

There are 3 types of objects you can create:

**Ropes**
.. image:: /_static/images/rope.gif
:width: 500
:alt: Rope gif

**Chains**
.. image:: /_static/images/chain.gif
:width: 500
:alt: Chain gif

**Force fields**
.. image:: /_static/images/force_fields.gif
:width: 500
:alt: Force field gif


To create a rope or a chain you need to have a *Profile object*. It defines the way rope/chain looks like (just take a look at the image below to understand better):
.. image:: /_static/images/rope_profile.png
:width: 500
:alt: Rope profile

Profile objects need to be properly modeled. Profile object for ropes should stretch along X axis:
.. image:: /_static/images/profile_for_ropes.png
:width: 500
:alt: Profile for ropes

Profile object for chains should also stretch along X axis, facing Z axis with its 'flat' side:
.. image:: /_static/images/profile_for_chains.png
:width: 500
:alt: Profile for chains

Also, make sure profile object is named properly. Profile objects for ropes must be named like 'Profile_Rope_SOMETHING YOU WANT', for chains - 'Profile_Chain_SOMETHING YOU WANT'.
Finally, make sure to 'Set origin to geometry' for your profile object, and apply Scale and Rotation (Ctrl+A -> Rotation & Scale).
