# InformationSecurity_task6

## x) Read and Summarize

### Quintin 2014

- Tor’s cryptography is functioning, main risks come from exploits, mistakes, or traffic analysis
- It is used by journalists, activists, and ordinary people, not just criminals
- It's funded partly by U.S. Navy but open source, no hidden backdoor
- Running relays is legal in the U.S., exit relays may attract scrutiny
- Tor Browser Bundle and Tails make it simple to use
- Slower than normal browsing, but speeds improve with more relays
- Not foolproof-logging in or careless use can expose identity

### Shavers & Bair 2016

#### Introduction

- Tor (The Onion Router) had a major influence on how people use the internet anonymously
- It is built on top of Firefox and designed to give users stronger privacy online

#### History and intended use of the onion router

- The main idea was to create secure and anonymous communication over the internet
- It was first developed by the U.S. but is no longer under U.S. control, today it is supported and improved by experts worldwide
- Researchers and investigators might analyze what remains on a computer after Tor has been used
- Another approach is to look for weaknesses in Tor to reveal a user’s identity, although some of these attempts are now impossible

#### How the onion router works

- Traffic is sent through several Tor relays, only the last node reveals the message in plain form, all others remain encrypted
- At each relay, one encryption layer is removed
- No node knows the full path, so it is not possible to trace back by brute force
- Each session follows a different route, making tracking harder
- Exit nodes pass their IP address to the final service
- The network runs through volunteers who operate the relays
- It is quite popular for criminals, because it is anynomous

#### Tracking criminals using tor

- Criminals are usually exposed because of their own mistakes, like poor operational security
- A known example is when Tor was compromised through a Firefox vulnerability
- The weakest link is often the user: e.g., allowing location data on websites undermines anonymity
- Attacks on Tor itself are costly but possible:
  - Overloading or disabling parts of the network
  - Taking over many entry/exit nodes
  - Man-in-the-middle interception attempts
- Investigators can uncover real IPs with tracking code:
  - Embedded in emails (risky, may alert target)
  - Hidden in attached documents (less obvious)
- Another strategy is catching suspects outside Tor by linking clear web info back to them
- Network admins can see Tor is being used, but not what’s inside the traffic
- Observers outside the Tor network cannot inspect content at all
- End-to-end encryption makes it even harder to monitor or deanonymize

## a) TOR Installation and Access

We already installed TOR in class, so this is how you start it
<img width="804" height="170" alt="image" src="https://github.com/user-attachments/assets/f6c9e2c2-2c96-4276-adbd-6c9fa308c129" />

We connect and make our way to Ahmia
<img width="1224" height="662" alt="image" src="https://github.com/user-attachments/assets/84bb6d56-65a3-45ea-833f-affe042085b0" />

## b) Browse TOR network

Well as said, the search engine we use is Ahmia.fi

Here is some marketplace for dark web developers where they sell something like scripts for a relatively high price. It is probably a scam though as most of them.
<img width="1160" height="601" alt="image" src="https://github.com/user-attachments/assets/8db14dfb-6fba-4555-a6db-40651945d0ef" />
<img width="1169" height="588" alt="image" src="https://github.com/user-attachments/assets/9cc8a777-7168-47fa-8acf-a9b4a9468ebe" />

There is a forum called DarkNetArmy, where people supposedly leak stuff, ask questions and try to sell something
<img width="1189" height="614" alt="image" src="https://github.com/user-attachments/assets/666a6ab0-b0a1-40e5-af3e-7d9c56062803" />

For the last one, CIA came to my mind, so I searched for it and this was the result. Apparently you can view articles written by some people regarding attacks on national security. At least that's my impression.
<img width="1188" height="732" alt="image" src="https://github.com/user-attachments/assets/8bb8a91f-3f32-4079-ab7d-b7ebc6cbac76" />

## Sources

https://terokarvinen.com/information-security/#h6-going-dark
https://www.eff.org/deeplinks/2014/07/7-things-you-should-know-about-tor
https://www.oreilly.com/library/view/hiding-behind-the/9780128033524/XHTML/B9780128033401000021/B9780128033401000021.xhtml#s0010

And all the links regarding the DarkNet, but I didn't put them in because I am not sure if it is safe for that matter
