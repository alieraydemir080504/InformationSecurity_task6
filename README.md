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

### Introduction

- Tor (The Onion Router) had a major influence on how people use the internet anonymously
- It is built on top of Firefox and designed to give users stronger privacy online

### History and intended use of the onion router

- The main idea was to create secure and anonymous communication over the internet
- It was first developed by the U.S. but is no longer under U.S. control, today it is supported and improved by experts worldwide
- Researchers and investigators might analyze what remains on a computer after Tor has been used
- Another approach is to look for weaknesses in Tor to reveal a user’s identity, although some of these attempts are now impossible

### How the onion router works

- Traffic is sent through several Tor relays, only the last node reveals the message in plain form, all others remain encrypted
- At each relay, one encryption layer is removed
- No node knows the full path, so it is not possible to trace back by brute force
- Each session follows a different route, making tracking harder
- Exit nodes pass their IP address to the final service
- The network runs through volunteers who operate the relays
- It is quite popular for criminals, because it is anynomous

### Tracking criminals using tor

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
