# PassGen

A targeted wordlist generator designed for Red Team reconnaissance and penetration testing.

## Project Overview
PassGen is a Python-based utility that automates the creation of personalized wordlists. By leveraging known information about a target (such as names, dates, or interests), it generates potential password candidates using common transformation patterns, complexity rules, and leet-speak variations.

## Features
- Targeted Permutations: Combines user-provided keywords into plausible password structures.
- Leet-Speak Engine: Automatically converts standard characters into common substitutes (e.g., e -> 3, a -> 4).
- Suffix/Prefix Padding: Appends common special characters and year patterns.
- Hashcat-Ready: Outputs results in a clean .txt format compatible with industry-standard cracking tools.

## Roadmap (Planned Features)
<!-- - [ ] Integration with common OSINT APIs to fetch public data. -->
- [ ] Multi-threading for faster generation of massive wordlists.
- [ ] Support for custom rule files (Hashcat style).

## Ethical Disclaimer
This tool is intended for authorized security testing and educational purposes only. Using this software to attack targets without explicit, prior consent is illegal. The developer assumes no responsibility for any misuse or damage caused by this program.
