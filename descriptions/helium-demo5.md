# Helium demo 5: Displays an audit trail for access to restricted data, including access to the same data from multiple stacks

A user authenticates in CommonShare via an Oauth-based system and
browses all the data sets for which she has an owner role.  Each
dataset is displayed as an icon on which she can right click to
display a menu of options. Among these options she selects “Request
audit trail” and is prompted with a window that displays logs with
detailed information about time of access, user and data operations
performed on the data object such permission changes, move, get and
put. Similarly, a user with audit role can authenticates through a
private API in CommonShare only accessible through a VPN and request
audit trail for active and inactive users that include all data access
operations that the user has performed in the last 30 days.

