# SkillChains for Horizon XI Private Server

### What's new compared to the original version?
This version of SkillChains has been modified to work with Horizon XI private server https://horizonxi.com/. The skills.lua file has been modified by DivoXI based on the skills.lua file found in https://github.com/NerfOnline/Chains-HorizonUpdated/releases/tag/v0.81 that's designed for Ashita v4.

Special thanks to NerfOnline, Hugin and all the contributors that made it possible to have a custom SkillChains for the Horizon XI private server. And special thanks to Ivaar the original author of this Windower addon https://github.com/Ivaar/Skillchains from which this project was forked.

### Active Battle Skillchain Display.

Displays a text object containing skillchain elements resonating on current target, timer for skillchain window,
along with a list of weapon skills that can skillchain based on the weapon you have currently equipped. 

    //sc color    -- colorize properties and elements
    
    //sc move     -- displays text box click and drag it to desired location.

    //sc save     -- save settings to current character.

    //sc save all -- save settings to all characters.

The following commands toggle the display information and are saved on a per job basis.

    //sc spell    -- sch immanence and blue magic spells.

    //sc pet      -- smn and bst pet skills.

    //sc weapon   -- weapon skills.

    //sc burst    -- magic burst elements.

    //sc props    -- skillchain properties currently active on target.

    //sc timer    -- skillchain window timer.

    //sc step     -- current weaponskill step information.

More settings related to text object can be found within the settings.xml, generated on addon load
