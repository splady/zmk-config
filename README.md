# zmk-config

This repo is my customized version of the [ZMK wireless keyboard firmware](https://zmk.dev/). <br>
Configured for a wireless [Corne keyboard](https://github.com/foostan/crkbd) running dual [nice!nano](https://nicekeyboards.com/nice-nano/) v2

<img width="5382" height="2549" alt="Splitboard" src="https://github.com/user-attachments/assets/ac0c3ee2-6196-4714-8e0b-e6f321f8e1da" />
This is my keyboard running this firmware. Airpods for scale

## Updating ZMK

ZMK is pinned to a commit for reproducible builds. Periodically update the commit
SHA in both `config/west.yml` and `.github/workflows/build.yml`, keeping the two
values identical, then confirm the GitHub Actions firmware build succeeds.
