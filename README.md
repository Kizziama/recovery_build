# Building Recovery Online Made Easy #

## Important Notice ##
### Users reported build errors forking to own account. ###
### To fix this, create a new organization, fork to the new organization. This fixes the problem, for now.

#### What This Is ####

This is an easy way for recovery maintainers or anyone who's interested in building recoveries to finish their dream without a server.

This works with GitHub actions, thank GitHub not me.

#### How To Use ####

Here are some useful notes to using this tool brewed with black magic.

1. Fork the repo to a organization

2. Go to action

3. Select "Building recovery" Workflow

4. Enter the variables which are mentioned

```MANIFEST : Link For Minimal Recovery Manifest; default is twrp minimal manifest```

```MANIFEST_BRANCH : Enter Manifest Branch Would You Like To Sync like, e.g. twrp-11```

```DT_LINK : Enter Link For Your Device Tree With Branch Like $URL -b BRANCH```

```VENDOR : Enter Your Device OEM, e.g. motorola, asus, xiaomi, etc.```

```DEVICE : Enter Your Device Code Name, e.g. rosy, sakura, curtana, etc.```

```LUNCHCMD : Enter Lunch Command like lunch omni_$device-eng or lunch twrp_$device-eng```

```BUILDCMD : Enter Build Command m recoveryimage or m bootimage```

```TW_DEVICE_VERSION : Set Custom Build Version```

```GH_TOKEN : Add GitHub Token in Secret Environment```

Optional

```EXTRA_CMD : Add Extra Commands To Run Before Build Start```

5. Click On "Run Workflow"

6. Star the repo, go to actions tab again, and let black magic go brrr.

If you don't know any of these, **Ask [Google](https://www.google.com) or someone who builds recoveries**, I don't provide TWRP building support.

You'd also like to do edits on your recovery device tree first if your recovery needs that (e.g. SHRP, etc.)

#### Credits and thanks and stuff like that ####

Made with blek magic by [***Jamie***](https://t.me/henloboi)

Infinite help from [***ElytrA8***](t.me/ElytrA8)

Recovery building help from [***Pulkit***](t.me/Pulkit077)

And lastly, all TWRP compiling help from Google.

Enjoy buildbotting.
