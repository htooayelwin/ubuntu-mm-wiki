#﻿General Notes

Ubuntu လမ္းညႊန္သည္ ပုဂၢလိကဆိုင္ရာကုမၸၸဏီႏွင့္ေသာ္လည္းေကာင္း အျခားစီးပြားေရး လုပ္ငန္းႀကီးမ်ားႏွင့္ေသာ္လည္းေကာင္း စီးပြားေရးအရသက္ဆိုင္မႈမရွိပါ။
Ubuntu သည္ သံုးစြဲသူမ်ားကို Menu ရုပ္ပံုအသံုးခ် Graphical User Interface  (GUI) ႏွင့္ေသာ္လည္းေကာင္း စာသားအသံုးခ် command line ဆိုင္ရာ text-based command-line interface (CLI) ေသာ္လည္းေကာင္း အလုပ္မ်ားကို လုပ္ေဆာင္ႏိုင္ေစပါတယ္။ Ubuntu တြင္(command-line-interface)ကို Terminal လို႕ေခၚပါတယ္။ Terminal ကိုစဖြင့္မယ္ဆိုရင္ Menu- Applications-Accessories - Terminal စသည္ျဖင္႔ အဆင့္တိုင္းသြားေရာက္ႏိုင္ပါသည္။ Terminal တြင္ ခဲေရာင္မ်ဥ္းအစက္မ်ားအတြင္း စာသားမ်ားကို ထည့္သြင္းအသံုးျပဳႏိုင္ပါသည္။

ကြန္ပ်ဴတာလုပ္ေဆာင္မႈစနစ္မွ ေျပာင္းလဲခ်က္မ်ားကို ေျပာင္းလဲခြင့္ရွိသူ (Admin အခြင့္ရွိတဲ့) အသံုးျပဳသူကပဲေဆာင္ရြက္ႏိုင္ပါသည္။ `sudo` Command က အသံုးျပဳသူကို ေျပာင္းလဲခြင့္ရွိသူ Admin အျဖစ္ ယာယီသတ္မွတ္ေပးသည္(ဥပမာ - ပရိုဂရမ္တစ္ခု သြင္းစဥ္ (သို႕) စနစ္ပိုင္းဆိုင္ရာေျပာင္းလဲစဥ္)။ နမူနာအေနျဖင့္ ေအာက္တြင္ေဖာ္ၿပထားသည္။

	sudo bash

`gksudo` ကို Graphical Application ေတြဖြင့္ရာမွာ `sudo` အစား Run Command မွေသာ္လည္းေကာင္း မီႏူးမ်ားမွေသာ္လည္းေကာင္း အသံုးျပဳႏိုင္ပါတယ္။နမူနာ အေနျဖင့္ ေအာက္တြင္ေဖာ္ၿပထားသည္။

	gksudo gedit /etc/apt/sources.list

ဖိုင္အမ်ားစုရဲ႕ ခန္႕ခြဲမႈေတြကို ရင္းျမစ္ျပင္ဆင္ခြင့္ရွိတဲ့ Admin  အခြင့္ (root Administrative privileges)ႏွင့္ Nautilus file မန္ေနဂ်ာကဲ့သို႕ အသံုးျပဳကာနဲ႕ ေဆာင္ရြက္ႏိုင္ပါသည္။ Munu မွတဆင့္ အသံုးျပဳမယ္ဆိုရင္ `gksudo` ကိုအသံုးျပဳပါ။

	gksudo nautilus (သို႕မဟုတ္) sudo nautilus

`man` ကေတာ့ ကြန္မန္းေတြအတြက္ အကူအညီလိုလာၿပီဆိုရင္ အသံုးျပဳႏိုင္ပါတယ္။နမူနာအေနနဲ႕ `man sudo` လို႕ရိုက္ထည့္လိုက္မယ္ဆိုရင္ `sudo` ကြန္မန္းနဲ႕ဆိုင္တဲ့
လက္စြဲဖိုင္စာမ်က္ႏွာေတြကိုျမင္ေတြ႕ရမွာျဖစ္ပါသည္။ 

	man sudo

`apt-get`  ႏွင့္ `aptitude` ေတြကို ပရိုဂရမ္ေတြ ပက္ေက့ (package) ေတြ ထည့္သြင္းရာမွာအျမန္ဆံုးနည္းအေနနဲ႕ အသံုးျပဳပါတယ္။ GUI ထည့္သြင္းမႈအတြက္ Synaptic Package Manager ကိုလဲအသံုးျပဳႏိုင္ပါတယ္။ ဒါေပမယ့္ ပရိုဂရမ္ေတြ ပက္ေက့ (package) အမ်ားစုဟာ `apt-get install` ႏွင့္ေရာ Synaptic Package Manager ႏွင့္ပါ ထည့္သြင္းႏိုင္ပါသည္။အခုလမ္းညႊန္မွာ ျမင္ေတြ႕ႏိုင္ပါသည္။

	sudo apt-get install package 

Synaptic မွာပက္ေက့ေတြ (package) ကိုရွာေဖြပံုနဲ႕ ထည့္သြင္းပံုက ဤသို႕ျဖစ္ပါသည္။ အမိန္႕ေပးမႈအမ်ားအျပားကို nano စာသား အယ္ဒီတာ အသံုးျပဳခိုင္းေစပါတယ္။ နာႏိုက
Linux တိုင္းမွာ ရရွိတဲ့ အယ္ဒီတာျဖစ္ပါသည္။ တစ္ခါတရံမွာ Ubuntu မွာပါတဲ့ gedit ထက္အသံုးျပဳရတာပိုလြယ္ပါတယ္။

Menu ဆိုတာကေတာ့ desktop အေပၚဘက္မွာရွိ မီႏူးဘားကို ရည္ညႊန္းပါတယ္။ မိုက္ခရိုေဆာ့ဖ္၀င္းဒိုးမွာရွိတဲ့ Start menu၊ Apple Macintosh မွာရွိတဲ့ Menu bar ေတြနဲ႕တူတူပါပဲ။

တကယ္လို႕ ၆၄ ဘစ္ ဗားရွင္းစနစ္ကို အသံုးျပဳမယ္ဆိုရင္ i386 ကို amd64 နဲ႕ အစားထိုးရမွာ ျဖစ္ပါသည္။

##Other Versions

လက္ရွိအသံုးျပဳေနတဲ့ Ubuntu version ကိုၾကည့္ခ်င္ရင္ Terminal ေပၚမွာ ေအာက္ပါအတိုင္းရိုက္ထည့္ၿပီး Enter ႏွိပ္ပါ။

	lsb_release -a

လက္ရွိအသံုးျပဳေနတဲ့ kernel ကိုၾကည့္ခ်င္ရင္ရင္ေတာ့ Terminal မွာ ေအာက္ပါအတိုင္းရိုက္ထည့္ၿပီး Enter ႏွိပ္ပါ။

	uname -a

##Newer Versions  of Ubuntu 

Ubuntu ကို ၆လလွ်င္တစ္ႀကိမ္ထုတ္ေ၀ၿပီး ႏွစ္စဥ္ ဧၿပီလႏွင့္ေအာက္တိုဘာလတို႕တြင္ ထုတ္ေ၀ပါသည္။ Oneiric Ocelot (11.10) (http://ubuntuguide.org/wiki/Ubuntu:Oneiric), မ်ားမႀကာမီ ေနာက္ဆံုးထြက္ေပၚမည့္ Oneiric ကို ၂၀၁၁ခုႏွစ္ ေအာက္တိုဘာလတြင္ အခမဲ့ ရယူႏိုင္မည္ျဖစ္ပါသည္။သို႕ရာတြင္ ၄င္းသည္ ကာလရွည္ႀကာ ေထာက္ပံ့မႈေပးသည့္ LTS Version မဟုတ္ပါ။

##Older Versions of Ubuntu

##Other Resources 

Ubuntu Forums (http://ubuntuforums.org/) တြင္ အြန္လိုင္းေျဖရွင္းခ်က္မ်ားႏွင့္ အျခားေသာအေသးစိတ္အခ်က္အလက္မ်ားကို ကူညီေပးရန္ အဖြဲ႕အစည္းမ်ားစြာ ရွိပါသည္။
ျပည္တြင္း အဖြဲ႕အစည္းအေနျဖင့္ Ubuntu for Myanmar (ubuntu-mm) (http://ubuntu-mm.net/) ရွိၿပီး ျမန္မာဘာသာျဖင့္ Ubuntu အေႀကာင္းေလ့လာႏိုင္ပါမည္။
####[ubuntu-mm.net](http://ubuntu-mm.net)
####[ask.ubuntu.com](http://ask.ubuntu.com)
####[FB Ubuntu-MM Group](http://fb.com/groups/ubuntu4mm)
####[FB Pages](http://fb.com/ubuntumm)
####[Ubuntu Myanmar LoCo Team](http://wiki.ubuntu.com/MyanmarTeam)
####[Ubuntu-MM LoCo](http://loco.ubuntu.com/teams/ubuntu-mm)

##Ubuntu Resources 

###Unity Desktop

[Unity](http://en.wikipedia.org/wiki/Unity_%28desktop_environment%29) ဆိုသည္မွာ Ubuntu တြင္ အသံုးျပဳသည့္ နဂိုမူလပါေသာ Desktop ပံုစံျဖစ္ပါသည္။ (Gnome) ဂႏုမ္းမွ အသံုးျပဳသည့္ GTK ပလက္ေဖာင္းျဖင့္ အဆင္ေျပသင့္ေတာ္ပါသည္။ netbook မ်ားတြင္ အသံုးျပဳရန္ ဒီဇိုင္းျပဳလုပ္ထားေသာ္လည္း အျခားေသာ စက္ပစၥည္းအမ်ိဳးအစားမ်ားတြင္ပါ အသံုး၀င္ေစရန္ canonical မွ ျပင္ဆင္ေပးထားပါသည္။

###Gnome Project 

[Gnome 3](http://www.gnome.org/) သည္ Ubuntu အတြက္ ပံုစံအသစ္အေနျဖင့္ ရယူႏိုင္ပါသည္။ Gnome လုပ္ငန္းစဥ္မ်ား (http://projects.gnome.org/) ႀကည့္႐ႈ ရယူႏိုင္ပါသည္။
