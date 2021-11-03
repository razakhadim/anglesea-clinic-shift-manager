# anglesea-clinic-shift-manager

1. Use DrawerLayout in your activity xml like what I did in the MainActivity.xml. Then add NavigationView in your xml document. 
2. set "android:id" to your own id and ensure that "tools:context" is your own activity's name
3. copy my code which be signed by comments line in the MainActivity.java, paste to your own activity.java. Then set "drawer=findViewById();" to your own xml drawerLayour id(which you did in step2).
4. go to AndroidManifest.xml , add "android:theme="@style/AppTheme.NoActionBar" into your <activity>. 

You may find the menu cover your screen. You can temporary delete  "tools:openDrawer="start"" this code. Then menu will disappear. But don't forget add it back at the end.

