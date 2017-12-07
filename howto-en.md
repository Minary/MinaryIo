---
layout: page
title: Howto
lang: en
permalink: /howto/
---

Minary can be started in two ways:
  - Double-clicking the Minary.exe file
  - Double-clicking a template file

Double-clicking Minary.exe will allow you to hand-craft an attack from scratch. This allows for tests and experiments in your own network.

Double-clicking a template file (filename extension: .mry) will perform all required steps for a specific attack automatically. Templates are used to attack a particular system (e.g. Facebook logins).
  
## Double-clicking Minary.exe

Double-click **Minary.exe** in the installation directory. Minary will open in a neutral state and can be configured for an attack. Before any attack, perform these three steps:
  * Activate the plugins you need for this particular attack
  * Scan the network for target computers to attack
  * Start your attack and watch the output in the plugin tabs

![Minary in a neutral state](/assets/minary/default_screen.png){:class="img-responsive"}
    
  
## Double-clicking a template file
A template file automatically configures Minary for a particular attack. Minary then goes through the following steps:
  - It loads the required modules and unloads any unnecessary ones
  - It scans the LAN for potential target systems (if activated)
  - It selects and activates those target systems (if activated)
  - It starts the attack (if activated)

You can generate templates yourself or you can download them from [the project page's findings section]({{ "/findings" | relative_url }}). Download a template file and double-click it to start the attack automatically.

![Minary started via template](/assets/minary/loading_template.png){:class="img-responsive"}

Please make sure to have started Minary at least once before. Otherwise Windows doesn't know what to do with the template file.
