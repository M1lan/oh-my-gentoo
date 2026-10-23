# OMG! -- OMGentoo -- oh-my-gentoo 

> a tongue-in-cheek reply to "omarchy" by DHH

## Day zero - a diary entry after 45 days 

OMG, basically like OMARCHY, takes inspiration from the concept behind "oh-my-zsh" and
similar projects and applies this concept to a Linux Distribution of choice.

I briefly contemplated NixOS and Omarchy but landed on Gentoo for many reasons.

NixOS: in theory, I'd say YES! to NixOS and flakes but I'd say HELL NAAAH to
home-manager. Only recently I had my try with NixOS, but that particular laptop was
stolen, maybe it's jinxed or rather: nix'ed.  So, I ended up saving for a year to afford a
maxed Framework 13 Pro Ryzen AI 300.

And I do honestly do believe this is going to be the very last laptop/notebook system and
with that operating system that I'll ever need to purchase; this one has the potential to
last me a lifetime.

---

My initial idea was to bootstrap from a stage3 to get a minimal running system, add claude
code and then go from there.  I then actually ended up installing claude code (and ollama)
first things first, immediately after booting into the minimal installation live iso from
USB and use it to go over the official Gentoo installation guide step-by-step while making
sure to apply all changes myself.  Later: auto-mode.

---

I have noticed, OMARCHY provides you with a certain choices for the O/S Graphical
Environment,- all of them highly opinionated. My idea is to keep things as basic and
simple as possible and stick to vanilla GNOME on wayland with Xorg as a fallback option
(and because wayland just cant do certain things yet, things I need like once per year
such as `ssh -Y`).

I do NOT care so much about the Desktop Env per se, but I do not want to work on the TTY
and I do want GNOME to take care of all the things that I want to ignore (dbus,
wallpapers, etc.).  Graphical web browser use and ability to do video calls probly the
only reason.


---

My idea is NOT to create a Distro for anyone, I do NOT want to create a Desktop
Environment for anyone and make choices for them -- that, in my book, should be left to
everybody themselves.

example: GhosTTY? Foot? Kitty? WezTerm? Alacritty? rxvt-unicode?  -> I dont really care
about this choice and it does not matter to me, but I do agree that I need to make a
choice here, so I decide for GhosTTY (actually Ghostel in Emacs, but also GhosTTY as a
fallback). 

The same holds for absolutely everything that's installed: nobody cares if you prefer
nano, vim, neovim, or Emacs and I am NOT there to make these choices for anyone.

---

So all the above (what people normally understand when they think "OS" or "Distro" -
basically "the Desktop UX/UI"),- is *not* what I want to focus on and I believe there is
no point in sharing any of that.  And yes, I also do not think much of "oh-my-*" projects,
which are basically inviting beginners to blindly accepting someone else's configuration
without any reflection. I think it's much better to build up your own setup and maybe rip
some ideas from here and there and integrate it yourself.

And at the very and stands raw muscle memory -- you no longer upload your dotfiles to a
repo, you know your way around an unconfigured system from scratch, no matter which system
and you'll intuitively build-up a config as you go along every time from muscle memory.

Blindly copying over someone else's maximalist configuration usually means you'll not need
or use most of that setup, because it's not your own, it's strange to you and you don't
know it inside-out.

So, this "batteries included" aspect, that is not the "OMG" aspect and conceptual frame I
want to use here. 

Instead, what I want to do is to design an AI-first Meta-distro that you can use to
quickly bootstrap your own tailor-made distro.  Why? Because imho Gentoo is frequently
misunderstood. It's not like Arch and it's not compliation-only-for-no-reason.  Gentoo is
a Meta-distribution, so a Distro that is perfect tookit to quickly and easily create and
bootstrap custom made linux distros from scratch.

And THAT is the "OMG" factor that I want to focus on. 

---

This means that if there ever will be a "distro" coming out of this project, it will be a
live usb similar to the Gentoo minimal installer, but with AI on board and meant to be
booted on modern systems on hardware that offers "AI" capacities such as the Ryzen AI 300;
or even Apple's Metal.. But I know that I'm not going to make oh-my-asahi linux. I do not
own a MacBook Pro and I don't care about ever owning one. 

The Framework Pro is much better.
