# docker file

I experimented a little with using docker for app sandboxing. While it sounds very cool in theory, I've learned that X forwarding (for GUI apps) makes for easy exploiting. Thus, I don't think docker is good enough for app isolation.

The one docker file I have here works for Linux Mint 17.2 and installs google-chrome with google-talk plugin.