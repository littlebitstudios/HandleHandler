# LittleBit's Handle Handler
This is a web app made for sharing social media handles.

# How it works
This website is designed around the ActivityPub handle format (@username@domain) used by Mastodon and other such social networks (collectively known as the Fediverse).

Going to https://handle.littlebitstudios.com/@littlebit670@mastodon.social would lead to my Mastodon profile.

But, it's not just for Fediverse platforms. https://handle.littlebitstudios.com/@littlebit670@x.com leads to my Twitter profile.

# Why this is open-source
I want people to be able to improve this, so I'm publishing this as open-source code. There's no way that I could implement every feature people would ask for.

# Currently supported handles
@username@domain:
- Mastodon
- Meta Threads
- Twitter
- Instagram
- TikTok
- YouTube
- Reddit
- Lens Protocol
  - hey.xyz
  - orb.club, orb.ac
- and possibly many others...

Formats without the second @ symbol:
- ENS domains (someone.eth)
- Bluesky Social standard usernames (someone.bsky.social)
- Some website domains (which may also function as ENS domains or Bluesky usernames)
  - .com
  - .net
  - .org
  - .io

# License and credits
I am not affiliated with any companies mentioned. As with all of my projects, I make things just because I had the idea to make them.

This project is open-source under the MIT License.