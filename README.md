icon-pack-blank-template
========================

Icon pack template that is compatible with Apex, Nova, ADW, Holo,etc..and also has ADW Iconpicker functionality.

Thanks to Sammycakes for code from the appfilter, bagarwa for the help with ADW Iconpicker and anyon else that has helped me to get this far.

As always if you are new to theming follow this tutorial http://forum.xda-developers.com/showthread.php?t=1649891 to get started.

Once you are ready open the IconPack.java file found in src/com/yourname/themename and add your details to the top.

Then open res/values/strings and fill in your info. The ADW Strings are for the icon picker activity. The hello string can be used as a description or a message to the user.

Want to add a dock pack for ADW? Open res/values/theme_config and change <bool name="enableDockPack">false</bool> to <bool name="enableDockPack">true</bool> and be sure to make your docks according to the ADW theme guide. 

ADW Github: https://github.com/AnderWeb/ADW.Theme-Template

I made a video for designers just getting started with icon packs. Can be found here: http://www.arandompackage.com/2013/04/tweak-apex-theme-sample-for-ultimate.html

For ADW Launcher. Wallpapers need to be placed inside res/drawable and named theme_wallpaper. Same goes for screenshots/previews. Name them theme_preview
