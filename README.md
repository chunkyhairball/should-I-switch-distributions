# should-I-switch-distributions

# Should I Switch Linux Distributions? A Guide...

It's been said that most people who want to switch Linux distributions are mistaking what makes a Linux Distribution and what makes a Desktop Environment. 

I don't entirely believe that's true. However, there are elements of the argument, especially to new Linux users, that may apply. I've done my best to organize my thoughts on the subject to help others make a choice on the matter.

## - I want my user interface or icons to look different, but work in fundamentally the same way:

What you're probably after here is a new theme. With some exceptions, most Linux Desktop environments and window managers are VERY 'skinnable' or 'themeable'. You can find huge assortments of themes simply by typing the name of your desktop environment and 'themes' into your search engine of choice. You'll find many curated lists.

https://www.pling.com/ is worth checking out. I personally don't use their Pling store app, preferring to manually install themes or to install them from the OS's package manager or theme manager if they're available there. https://www.deviantart.com/ is also a good place to look.

You may also be after new fonts. Again, your distribution's package manager probably has lots, but check out fonts.google.com for a wealth of installable fonts. Again, fonts are very likely to be available from your package manager

A good example: When Garuda Linux (https://garudalinux.org/) first started gaining traction, many people were excited by its new look and wanted to switch to it.

Garuda Linux's 'look' comes primarily from its carefully chosen theming, including icons from the Beautyline and Candy icon sets: https://github.com/Tekh-ops/Garuda-Linux-Icons

Those icons, fonts, and themes can be downloaded and installed on *any* Linux distribution and not just Garuda.

## - I want my user interface to work in a different way:

This one's a bit trickier. Usually, what newer Linux users are told is that what they're probably after is a new Desktop Environment or Window Manager. If you're frustrated with the way Gnome Desktop (https://www.gnome.org/) works, then looking at KDE Plasma (https://kde.org/plasma-desktop/) may be a good idea and vice-versa. Some users find that they prefer working almost solely with the keyboard rather than a keyboard and mouse combination. For these users, a tiling Window Manager such as i3 (https://i3wm.org/) might be interesting. Additionally, you can download and install many shell extensions that change the way your particular Desktop Environment works.

With a few exceptions, you can install most Desktop Environments and Window Managers from your distribution's Package Manager without first removing an existing environment. Then, when you next login, you can switch to the new environment or use the existing environment if you feel the need to switch back.

Here's where it gets a bit tricky: In several cases, there are complex interactions between desktop environments and the rest of the operating system that have the potential to cause conflicting system components to be installed. If your package manager refuses to install one Desktop Environment without first uninstalling large parts of another, this may be what you're up against.

Frequently, the least complex way to install a new desktop environment is often to first back up your data and then install the same operating system you're used to, but taking care to select the 'flavor' of that operating system containing the Desktop environment you want.

Again taking Garuda as an example, the Garuda Linux website offers many different downloads as 'Editions', featuring different Desktop Environments or Window Managers:

https://garudalinux.org/downloads.html

Some distributions refer to these as 'Flavors' or 'Spins'.

## - I want to use applications that are offered with another Linux Distribution that are not installed with mine:

Many Linux Distributions exist for the sake of showcasing a particular application or set of applications. In almost all cases, however, those applications can be downloaded and installed on other Linux OSes from your default package manager.

In this case, it's simply unwise to install a new operating system just to get a new application. First search your OS's Package Manager to see if that application is available for install. If that doesn't work, look at manual installation steps on the application's website. Many applications are now offering 'containerized' versions to download in the popular Flatpak or Appimage formats that can be downloaded and installed very easily.

If you can't immediately install that new app from your package manger, check https://flathub.org to see if it's available as a Flatpak.

## - I want to learn the differences between different Linux Distributions:

This is a fairly good reason for switching to a new distribution. Different distributions have different ways of handling package management, administration, and security. Remember, however, that they all sit on top of the Linux Kernel. There's not going to be profound difference between the way Debian (https://www.debian.org/) and Arch (https://archlinux.org/) work when compared to, say, Windows and MacOSX.

It's also worth noting that most Linux distributions derive from only a handful of parent distributions.

Take a gander at this somewhat dated 'Linux Family Tree' to get an idea of how this works:

https://futurist.se/gldt/wp-content/uploads/12.10/gldt1210.png

If you're currently using, say, Linux Mint (https://linuxmint.com/) and want to try Pop! OS (https://pop.system76.com/), remember that those are both derived from Ubuntu Linux (https://ubuntu.com/), which is itself a derivation of Debian Linux. You're not going to notice a tremendous difference between them.

Now if you switch from Ubuntu to something like Suse Linux (https://www.suse.com/), the changes become significantly more noticeable. Suse is set up to be administered in a somewhat different way from Ubuntu. These are not aesthetic differences, but instead are differences in the way the package manager applications work or system setup and administration behaves.

Before switching for this reason, take the time to understand what 'family' your Linux distribution belongs to and what another family may offer or how it differs.

## - My distribution is very full-featured and comes with lots of preinstalled software. I want to switch to a distribution that's much more minimal and allows for greater customization:

This is a fairly reasonable reason to switch Linux Distributions. Many Linux-based Operating Systems make a lot of effort to position themselves to be usable by beginners or newcomers to Linux.

(These tend to be, but are not always, in the 'Debian' family of OSes-- Ubuntu, Pop!, Mint, etc...)

Other distributions are less 'hand-holdy' and are aimed at more technically proficient users, hobbyists, and tinkerers. Arch- and Gentoo-based (https://www.gentoo.org/) OSes are good examples.

There is, of course, a rainbow of alternatives in between. Before making the decision to switch, be sure to check out as much of the documentation for the OS you're considering as possible, especially the installation instructions.

This is very much a 'look before you leap' situation. Caveat Emptor!

## - I'm currently looking to move from a 'Long-term Support' distribution to a 'Rolling Release' distribution.

Again, this is very much a valid reason to want to change distributions. However, there are some VERY important caveats.

By definition, your Long-term distribution has a LOT more testing and bug-fixing built into it than any given Rolling distribution. Even then, important bug-fixes, like security updates and the like,  are rolled out very promptly by almost all Linux Distributions, even those that seem 'stuck in the mud'.

Rolling Release-type distributions offer access to cutting edge software releases and experimental packages, but that often at a cost of that more exhaustive testing. In some cases, packages are made available as soon as they compile correctly.

Using the car analogy, Long-term Support distributions are the well-worn daily drivers that can always be depended upon to get you from point A to point B, requiring only routine maintenance. Rolling Release distributions are the cars favored by tuners and tinkerers, those who *want* to experiment and test different setups.

The most important facet of this discussion to take away is the fact that, simply due to that amount of time spent testing, bugs and security problems sneak into Rolling Releases more often. If you have important data or work to do and aren't absolutely sure how well that data is backed up or how quickly you can regain that workflow, stick to the more stable Long-term Support distributions.

## Summary

I hope that this document is helpful to newer Linux users trying to make good decisions about their OS. Additionally, a good way to add to your decision-making knowledge is to read the discussion forums on Reddit and on the OS's websites. That can give you a better, more realistic idea of what different distributions can offer you.

If you have any suggestions for improvements to this document, don't hesitate to let me know.

This document and any updates to it will be available at https://github.com/chunkyhairball/should-I-switch-distributions .
