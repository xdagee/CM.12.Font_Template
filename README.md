# CM.12.Font_Template
Base template for cyanogen's theme engine.

# how to use the template
Import into android studio and for it to build and sync all the necessary files.

Edit the AndroidManifest.xml file under \app\src\main\AndroidManifest.xml.

Edit package name to suite your preference
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.xdagee.cm12font_template">
...
</manifest>

Copy your fonts into \app\src\main\assets\fonts

Rename all fonts into roboto-"style_name"

Now goto strings.xml under \app\src\main\res\values\string.xml.
Edit the values to your preference
<resources>
    <string name="theme_name">CM.12.Font_Template</string>
    <string name="theme_author">Your Name</string>
    <string name="theme_email">something@yourdomain.com</string>
</resources>

Save all, rebuild and generate signed apk
enjoy...
