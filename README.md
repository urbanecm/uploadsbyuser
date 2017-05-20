# uploadsbyuser

This tool returns number of uploads by certain user on Wikimedia Commons site. The username is supplied by the `user` GET parameter. If the parameter isn't supplied, the tool returns `nouser`. If the supplied user do not exist, 0 is returned. It is supposed to be used for solving https://github.com/commons-app/apps-android-commons/issues/654.

# Example use
https://tools.wmflabs.org/urbanecmbot/uploadsbyuser/uploadsbyuser.py?user=Jagro returns 7281. 
